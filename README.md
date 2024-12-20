# Quillcraft 📝✨

Quillcraft is a dynamic and feature-rich blog application built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js). It enables users to create, manage, and share blog posts with a user-friendly interface while supporting complete CRUD (Create, Read, Update, Delete) operations.

## Features ✨

- **User Authentication**:
  - Secure login and signup functionality.
- **Blog Management**:
  - Create, edit, and delete blog posts.
  - View detailed blog content with an optimized layout.
- **Rich Text Editing**:
  - A WYSIWYG editor to format blog content seamlessly.
- **Comments and Likes**:
  - Allow users to comment on and like blog posts.
- **Bookmarking**:
  - Users can bookmark blogs to revisit later.
- **Responsive Design**:
  - Built with **Tailwind CSS**, ensuring a modern and mobile-friendly experience.
- **SEO-Friendly**:
  - Structured data and meta tags to improve discoverability on search engines.

## Tech Stack 🛠️

- **Frontend**: React.js with Context API/Redux for state management.
- **Backend**: Node.js and Express.js.
- **Database**: MongoDB with Mongoose for efficient data modeling.

## Installation & Setup 🚀

Follow these steps to run Quillcraft locally:

### Prerequisites:
- Node.js (v14 or later)
- MongoDB (local or cloud instance)

### Steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/sahil-578/QuillCraft.git
   ```
2. **Install Dependencies:**
   - For the server:
     ```
     cd Backend
     npm install
     
   - For the client:
    ```
    cd Frontend
    npm install
    
3. **Set Up Environment Variables:**
  - Create a .env file in the server directory and add the following:
    ```
    PORT 
    MONGODB_URI
    CORS_ORIGIN 
    ACCESS_TOKEN_SECRET 
    ACCESS_TOKEN_EXPIRY
    REFRESH_TOKEN_SECRET
    REFRESH_TOKEN_EXPIRY
    CLOUDINARY_API_SECRET
    CLOUDINARY_API_KEY
    CLOUDINARY_CLOUD_NAME
  
4. **Set Up Environment Variables:**

   - Start the server:
     ```
     cd Backend
     npm run dev

- Start the client:
     ```
     cd Frontend
     npm run dev

**Video Demonstration**

- Here’s a video demonstrating how to use the application:

https://github.com/user-attachments/assets/27cb31ad-e70d-481e-a224-39c5db10511c
