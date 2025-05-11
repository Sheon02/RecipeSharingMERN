# 🍽️ MERN Recipe Sharing Web Application  

## 📌 Introduction  
Welcome to the Recipe Sharing Web App, a full-stack MERN application that allows users to create, share, browse, and save their favorite recipes. The platform is designed to provide a seamless and interactive experience for food enthusiasts to connect over cooking.

## 🛠️ Technologies Used  

### **Frontend**  
- **React.js** – Building responsive and dynamic user interfaces  
- **HTML5 & CSS3** – Markup and styling  
- **JavaScript (ES6+)** – Functionality and interactivity  
- **Redux Toolkit** – State management  
- **Axios** – HTTP requests to backend  

### **Backend**  
- **Node.js** – JavaScript runtime environment  
- **Express.js** – Web framework for RESTful APIs  
- **Mongoose** – MongoDB object modeling  

### **Database**  
- **MongoDB Atlas** – Cloud NoSQL database  

### **Authentication**  
- **JWT (JSON Web Tokens)** – Secure authentication  
- **Bcrypt** – Password hashing  

### **Additional Tools**  
- **Cloudinary** – Image upload and storage  
- **React Icons** – Icon library  

## 🚀 Features  

- 👨‍🍳 **User Authentication**  
  - Secure registration/login with JWT  
  - Password hashing with bcrypt  

- 📝 **Recipe Management**  
  - Create, edit, delete recipes  
  - Rich text formatting for instructions  
  - Image uploads with Cloudinary  

- 🔍 **Discovery Features**  
  - Search by title/ingredients  
  - Filter by categories (Vegan, Desserts, etc.)  
  - Sort by rating/date  

- ❤️ **Social Features**  
  - Save favorite recipes  
  - Rate and comment on recipes  
  - User profiles with recipe collections  

## 📦 Getting Started  

### **Prerequisites**  
- Node.js (v16+)  
- MongoDB Atlas account  
- Cloudinary account (for image uploads)  

### **1. Clone the Repository**  
bash
git clone https://github.com/your-username/mern-recipe-app.git
cd mern-recipe-app  

### **2. Backend Setup**  
cd backend  
npm install  
### Create .env file:

env  
MONGO_URI=your_mongodb_atlas_connection_string  
JWT_SECRET=your_jwt_secret_key  
PORT=5000  
CLOUDINARY_CLOUD_NAME=your_cloud_name  
CLOUDINARY_API_KEY=your_api_key  
CLOUDINARY_API_SECRET=your_api_secret  
### Start server:  

bash  
npm run dev  
### **3. Frontend Setup**
bash  
cd ../frontend  
npm install  
### Create .env file:

env  
REACT_APP_API_URL=http://localhost:5000  
### Start application:  

bash  
npm start  
Visit: http://localhost:3000  

## 🌐 Project Structure  
mern-recipe-app/  
├── backend/  
│   ├── config/         # Database and cloudinary config  
│   ├── controllers/    # Route controllers  
│   ├── middleware/     # Auth middleware  
│   ├── models/         # Mongoose models  
│   ├── routes/         # API routes  
│   ├── utils/          # Helper functions  
│   └── server.js       # Express server  
│  
├── frontend/  
│   ├── public/         # Static assets  
│   └── src/  
│       ├── assets/     # Images, styles  
│       ├── components/ # Reusable UI  
│       ├── features/   # Redux slices  
│       ├── pages/      # Application views  
│       ├── services/   # API calls  
│       └── App.js      # Main component  
│
├── .gitignore  
├── LICENSE  
└── README.md  
Happy Cooking! 👨‍🍳 Happy Coding! 👨‍💻
