# Library-Central

**Library-Central** is a multi-user library management system built with the MERN stack (MongoDB, Express.js, React.js, Node.js) and Material UI for the user interface. It enables librarians to maintain sections and e-books while allowing users to browse, request, and manage e-books. The platform functions like an online library, facilitating the issuing, revoking, and management of e-books across various sections.

## Demo Video
Check out our demo video to get a quick overview of Library Central's features and how to use them.<br/>
[Watch Demo Video](https://www.youtube.com/watch?v=RS56igZdGEs)

## Features

### Roles and Responsibilities
The Library-Central application supports two distinct roles: Librarian and User. Each role has specific responsibilities and permissions within the system to ensure effective management and utilization of library resources.
- **Librarian**
  - Manage sections and e-books in the library.
  - Monitor users and track library statistics.
  - Grant or revoke access to e-books.
  - View and manage user feedback on e-books.
  
- **User**
  - Browse available sections and e-books.
  - Request up to 5 e-books at a time.
  - Update profile and rate e-books.

 ### Core Functionalities
1. **Authentication and Authorization**
   - Role-based access control using JWT tokens.
   - Single librarian role maintained in the system.

2. **Librarian Dashboard**
   - View application statistics: active users, total sections, total e-books and total issued e-books.
   - View all existing library users and delete users if necessary.

3. **User Dashboard**
   - View all e-books assigned to the user.
   - Open and read the e-books.
   - Provide feedback on issued e-books.

4. **Section Management** - for the librarian
   - **Manage Sections:** Create, update, and delete sections in the library.
   - **Display Sections:** View sections in a table with fields for name, description, and creation date. Includes options for editing and deleting.

5. **E-Book Management** - for the librarian
   - **Manage E-Books:** Add, edit, and remove e-books within sections.
   - **Display E-Books:** View e-books in a table with fields for name, author, and section. Includes options for editing and deleting.
   - **Search and Filter:** Search e-books by name, author, or section, with options to clear individual search filters.

6. **Request Management** - for the librarian
   - **View Requests:** Display pending requests and granted books in separate tables. Each table includes columns for book name, username, and action buttons.
   - **Handle Requests:** Approve or reject pending requests with corresponding buttons. Update the status of requests accordingly.
   - **Revoke Access:** Revoke e-books from users if their return date has passed or if needed. This updates the request status and removes the e-book access.
  
7. **Feedback Management** - for the librarian
   - **View Feedbacks:** Display feedbacks in a table with columns for e-book name, username, comment, rating, and action. Includes options for deleting feedback.
   - **Delete Feedback:** Delete feedback items with confirmation dialog.
  
8. **Available Books** - for the user
   - **Search and Filter:** Allows users to search for e-books by name, author, and section, with options to clear filters.
   - **E-Book Listing:** Displays a table of available e-books with columns for book name, author(s), and section. Includes a "Request" button for users to request an e-book.