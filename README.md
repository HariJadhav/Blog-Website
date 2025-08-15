ValueBlog is a full stack MERN blog web application controlled entirely by an admin. Only the admin can create, update, or delete blog posts. It features a rich text editor that allows formatting text, adding hyperlinks, inserting images, and embedding videos.

The application is fully responsive and displays all published blog posts on the home page in chronological order. Each post shows the author name, date, and time of creation. Visitors can browse the blog but cannot make changes unless they are the admin.

The front end is built with HTML, CSS, JavaScript, and React. React Router DOM is used for navigation between pages. The rich text editor is implemented using ReactQuill. The back end is powered by Node.js and Express, and MongoDB is used as the database to store blog content, metadata, and user information. JSON Web Tokens (JWT) are used for authentication to ensure only the admin can access the post management features.

During development, CRUD (Create, Read, Update, Delete) operations were implemented and tested using Postman. The application follows a modular structure, with the front end and back end separated into client and server folders.

Key features include:

* Fully responsive design for desktop and mobile devices
* Rich text editing with image, video, and link embedding
* Blog listing in chronological order with metadata
* Admin-only access for content management
* Secure authentication using JWT

Future enhancements could include enabling guest user accounts, implementing a search bar with filters, adding tags to blogs, allowing comments and upvotes, and integrating social media sharing options.


