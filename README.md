# 📸 InstaThought - Full Stack CRUD Application

InstaThought is a social media-inspired web application that allows users to share their thoughts and images. This project was built to master **RESTful API design** and the **MVC (Model-View-Controller)** pattern using the Node.js ecosystem.

## 🚀 Features
- **Full CRUD Functionality**: Create, Read, Update, and Delete posts seamlessly.
- **Image Uploads**: Integrated `Multer` to handle multipart/form-data for image processing.
- **Unique Identification**: Utilizes `UUID` for generating unique post IDs.
- **Responsive UI**: Custom CSS with interactive hover effects and a clean, modern layout.
- **Method Overriding**: Support for `PATCH` and `DELETE` requests directly from browser forms.

## 🛠️ Tech Stack
- **Backend**: Node.js, Express.js
- **Frontend**: EJS (Embedded JavaScript Templates), CSS3
- **Tools**: Multer (Image handling), UUID (Unique IDs), Method-Override

## 📂 Project Structure
```text
├── index.js          # Main server file & API routes
├── public/           # Static files (CSS, Images, Uploads)
├── views/            # EJS Templates (Index, New, Edit, Show)
├── package.json      # Project dependencies & scripts
└── .gitignore        # Files ignored by Git (node_modules)
