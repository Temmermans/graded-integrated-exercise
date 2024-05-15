### Assignment: Build an Admin Portal for "BookNest" Store

#### Overview
In this project, you will create an admin portal for "BookNest," a fictional bookstore. This portal will serve as a management tool for the bookstore’s inventory, allowing administrative users to add, update, and delete book entries. Regular users will be able to view the bookstore's catalog without authentication.

#### Project Goals
- **Frontend**: Develop the user interface using React.js focusing on reusable components.
- **Backend**: Build the server with Express.js, interfacing with a SQLite3 database, and implementing secure routes for admin functionalities.
- **Usability**: Ensure the portal is user-friendly, with efficient navigation and responsive design.

### Backend Specifications
1. **Database Setup**: Use SQLite3 to manage data storage.
   - Tables should include at least `books` and `admins`.
   - `books` table includes fields such as `id`, `title`, `author`, `isbn`, `price`, `image_url`, and `description`.
   - `admins` table manages admin credentials and roles.
   - Other tables might be needed depending on other things you want to do.

2. **API Development**: Create RESTful APIs using Express.js.
   - Public endpoints that list all books and get details for a single book.
   - Protected endpoints for adding, updating, and deleting books, accessible only to admins.

3. **Image Uploads**: Implement Multer for handling image uploads associated with book entries.

4. **Authentication and Authorization**:
   - Implement JWT-based authentication to secure admin endpoints.
   - Ensure that actions such as add, update, and delete operations on book records are restricted to authenticated admin users.

### Frontend Specifications
1. **React Components**:
   - Create small, maintainable components such as `BookList`, `BookDetail`, `Login`, `AdminDashboard`, and others.
   - Utilize React Router for navigation between components.

2. **State Management**:
   - Use React context for state management across the application.
   - Ensure proper state updates when performing CRUD operations.

### Additional Features
1. Must have - **Book Search Functionality**: 
   - Search through the names of the books
  
2. Nice to have - **Book Facet Search Functionality**: 
   - Implement a search feature to find books by author, ISBN or more.

3. Nice to have - **Nearest Store Locator**:
   - Include a feature to help users find the nearest BookNest store using geolocation API.

4. Nice to have - **Book Reviews**:
   - Allow users to read and submit reviews for different books.

5. Nice to have - **Bulk Uploads**:
   - Allow admins to upload book details in bulk through CSV file uploads.

### Submission Guidelines
- Your project should be submitted via GitHub, containing both frontend and backend code (also the sqlite database file).
- Include a README.md file with setup instructions, including how to install dependencies, configure the environment, and run the application if needed.

### Evaluation Criteria
- **Functionality**: All specified requirements must be met.
- **Code Quality**: Code should be clean, well-organized, and properly commented.
- **Design and Usability**: The application should be easy to navigate and visually appealing.
- **Security**: Application must securely handle user data and protect against common vulnerabilities.

Good luck, and happy coding!
