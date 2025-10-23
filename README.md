# EduConnect

[![React](https://img.shields.io/badge/React-18.2.0-blue?logo=react&logoColor=white)](https://reactjs.org/) 
[![Node.js](https://img.shields.io/badge/Node.js-18.x-green?logo=node.js&logoColor=white)](https://nodejs.org/) 
[![Express](https://img.shields.io/badge/Express.js-4.18.2-black?logo=express&logoColor=white)](https://expressjs.com/) 
[![MongoDB](https://img.shields.io/badge/MongoDB-7.0.3-green?logo=mongodb&logoColor=white)](https://www.mongodb.com/) 
[![Razorpay](https://img.shields.io/badge/Razorpay-Payment-blue)](https://razorpay.com/)

**EduConnect** is a full-stack MERN EdTech platform that enables instructors to create and manage courses while students securely enroll and access learning content. The platform focuses on secure authentication, smooth UX, and seamless payment integration.

---

## Tech Stack
- **Frontend:** React.js, Tailwind CSS, Redux Toolkit  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT, Bcrypt  
- **Payment Gateway:** Razorpay  
- **Other Tools:** Cloudinary (file upload), Node-schedule, Axios  

---

## Features
### Instructor
- Create, update, and manage courses with rich content.  
- Monitor student enrollments and payments.  

### Student
- Browse and enroll in courses securely.  
- Make payments via Razorpay to access courses instantly.  
- Track learning progress using interactive features.  

### Security & Performance
- Secure authentication and authorization using JWT and Bcrypt.  
- RESTful APIs for smooth frontend-backend communication.  
- Efficient state management with Redux Toolkit.  
- Scalable file uploads with Cloudinary.  

---

## Demo
![EduConnect Demo](./assets/demo.png)  
*Screenshot of EduConnect user dashboard (replace with your actual screenshot)*  

---

## Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/Mudassar123khan/EduConnect
   cd EduConnect
2.Install frontend dependencies:
  ```bash
  npm install
  ```
3.Install backend dependencies:
  ```bash
  cd server
  npm install
  ```
## Create a .env file in the server/ folder with required variables:
  ```bash
  MONGO_URI=<your_mongodb_uri>
  JWT_SECRET=<your_jwt_secret>
  RAZORPAY_KEY_ID=<your_key_id>
  RAZORPAY_KEY_SECRET=<your_key_secret>
  CLOUDINARY_CLOUD_NAME=<cloud_name>
  CLOUDINARY_API_KEY=<api_key>
  CLOUDINARY_API_SECRET=<api_secret>
  ```

## Running the Project:
  ```bash
  npm run dev
  ```
## Project Structure:
  ```bash
  EduConnect/
  ├─ server/              # Backend logic, APIs, MongoDB models
  ├─ node_modules/        # Project dependencies
  ├─ public/              # React public assets
  ├─ src/                 # React frontend code
  ├─ package.json         # Frontend scripts & dependencies
  ├─ server/package.json  # Backend scripts & dependencies
  ├─ .env                 # Backend environment variables
  └─ README.md
  ```
## Future Enhancements:
   1.Live video streaming for courses.

   2.Quizzes and certifications for students.

   3.Admin dashboard for monitoring platform activity.

# License
  This project is licensed under the MIT License.
