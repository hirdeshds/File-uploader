# File Upload App with Authentication

A Node.js + Express + MongoDB web application that allows users to sign up, log in, and upload image files.

## ✨ Features

- User authentication (Sign up / Login / Logout)
- Secure password hashing with bcrypt
- File upload with Multer
- Image preview
- MongoDB Atlas integration with Mongoose
- Environment variables using dotenv

## 📁 Folder Structure
```bash
    upload-app/
        ├── models/
        │   └── User.js
        ├── public/
        │   └── styles.css
        ├── uploads/                (ignored)
        ├── views/
        │   ├── homepage.ejs
        │   ├── login.ejs
        │   ├── signup.ejs
        │   └── success.ejs
        ├── .env
        ├── .gitignore
        ├── index.js
        └── package.json



