# EduConnect

[![React](https://img.shields.io/badge/React-18.2.0-blue?logo=react&logoColor=white)](https://reactjs.org/) 
[![Node.js](https://img.shields.io/badge/Node.js-18.x-green?logo=node.js&logoColor=white)](https://nodejs.org/) 
[![Express](https://img.shields.io/badge/Express.js-4.18.2-black?logo=express&logoColor=white)](https://expressjs.com/) 
[![MongoDB](https://img.shields.io/badge/MongoDB-7.0.3-green?logo=mongodb&logoColor=white)](https://www.mongodb.com/) 
[![Razorpay](https://img.shields.io/badge/Razorpay-Payment-blue)](https://razorpay.com/)

EduConnect is a full-stack MERN EdTech platform where anyone can come and learn what they want. The platform supports three distinct roles — **Student**, **Instructor**, and **Admin**. Instructors can list their courses, students can purchase and learn from them, and admins can monitor all platform activities for smooth operation and security.

---

##  Tech Stack

**Frontend:** React.js, Tailwind CSS, Redux Toolkit  
**Backend:** Node.js, Express.js  
**Database:** MongoDB  
**Authentication:** JWT, Bcrypt, OTP via Email  
**Payment Gateway:** Razorpay  
**Other Tools:** Cloudinary (file uploads), Node-schedule, Axios, Nodemailer

---

##  Features

###  Student
- Create an account, verify OTP via email, and log in securely.  
- Browse available courses and purchase them through **Razorpay**.  
- Access purchased courses and track learning progress.  
- Receive confirmation emails upon successful registration.  
- Communicate with the admin through the **Contact Us** section via email.

###  Instructor
- Create, manage, and update courses with rich multimedia content.  
- Monitor enrolled students and their payments.  
- Manage course visibility and availability in real-time.

###  Admin
- Monitor platform-wide activity, including user and course management.  
- Handle communication requests from students and instructors.  
- Ensure secure platform operations and manage database integrity.

---

##  Security & Performance

- **JWT-based authentication** and **bcrypt** password hashing for secure user access.  
- **Email-based OTP verification** for additional security during sign-in.  
- **Razorpay integration** for smooth and secure payments.  
- **Cloudinary integration** for scalable media file storage.  
- **Redux Toolkit** for efficient and consistent state management.  
- Fully **responsive UI** optimized for mobile, tablet, and desktop devices.

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

## License
  This project is licensed under the MIT License.

## Author
Mohd Mudassir Khan
Hotel & Property Booking Platform Developer
📧 12mudassarkhan@gmail.com

# ⭐ If you like this project, consider giving it a star on GitHub!
