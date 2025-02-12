# **User-Management-App**

## 🌐 GitHub Repo  
```bash
https://github.com/Prakashsaw/User-Management-App
```

## 🚀 Live Demo  
```bash
https://user-crud-app-prakash.netlify.app
```

## 📌 Description  
The **User Management System** is a web-based application designed to help a owner to efficiently track and manage their users/employees.  

### 🔹 Key Functionalities:  
- **User Authentication:** Secure login & registration with **email verification** through OTP.  
- **Password Security:** **Bcrypt** encryption for passwords and **JWT token-based authentication**.  
- **User Auth:** Implemented auth middleware for secure user auth and for protected routes.
- **Password Recovery:** Forgot password functionality with email-based reset link.  
- **User Management:** Add, edit, delete, and categorize users with filtering options and search functionality.  

---

## 🛠 Tech Stack  

### **Frontend:**  
- React.js, Bootstrap, CSS  

### **Backend:**  
- Node.js, Express.js, Nodemailer

### **Database:**  
- MongoDB  

---

## ⚙️ Run Locally  

### **Step 1: Clone the project**  
```bash
git clone https://github.com/Prakashsaw/User-Management-App.git
```

### **Step 2: Navigate to the project directory**  
```bash
cd User-Management-App
```

### **Step 3: Install dependencies**  

#### Install dependencies for the frontend  
```bash
cd client/
npm install
```

#### Install dependencies for the backend  
```bash
cd server/
npm install
```

### **Step 4: Set up environment variables**  
Create a **.env** file inside the `server/` directory and add the following:  
```bash
MONGO_URL = 
PORT = 
JWT_SECRETE_KEY = 
EMAIL_HOST = 
EMAIL_PORT = 
EMAIL_USER = 
EMAIL_PASS = 
EMAIL_FROM = 
CLOUDINARY_CLOUD_NAME = 
CLOUDINARY_API_KEY = 
CLOUDINARY_API_SECRET = 
```

### **Step 5: Start the application**  

#### Start the frontend  
```bash
// Open a new terminal
cd client
npm run start
```

#### Start the backend  
```bash
// Open a new terminal
cd server
npm run start
```

### **Step 6: Access the app**  
Once the setup is complete, the app will be running on your local system.  

---

## 🔥 Features  

- **🔒 Multiple User Login/SignUp options:** Sign In with Google, LinkedIn, Facebook and GitHub.
- **🔒 Secure User Authentication:** Register, login, and logout securely.  
- **📧 Email Verification:** Verify accounts via a confirmation OTP sent to the email and through OTP verification.  
- **🔑 Password Management:** Forgot password functionality with email reset link.  
- **🔑 Protected Routes:** Secure protected routes through middleware implementation.
- **💰 User Management:**  
  - Add, edit, and delete users with confirmation prompts.   
 
---

## 📸 Screenshots  

### **Authentication & User Management**  
| Feature | Screenshot |
|---------|-----------|
| **Homepage** | ![Homepage](/images/1-Home-page.png) |
| **Multiple Option for Sign In** | ![Multiple Option for Sign In](/images/2-multi-signin.png) |
| **Multiple Option for Sign In** | ![Multiple Option for Sign In](/images/3-multi-signup.png) |
| **Sign Up with Email** | ![Sign Up with Email](/images/4-sign-up.png) |
| **Verify Email Account With OTP** | ![Verify Email Account With OTP](/images/5-verify-email.png) | 
| **Login With Email** | ![Login With Email](/images/6-login.png) |
| **User Management Home Page** | ![User Management Home Page](/images/7-user-home-page-2.png) |
| **Add New User** | ![Add New User](/images/8-add-user.png) |
| **Update User** | ![Update User](/images/10-update-user.png) |
| **Updated User** | ![Added User](/images/9-user-home-page.png) |
| **Forgot Password** | ![Forgot Password](/images/11-forgot-password.png) |
| **Forgot Password** | ![Forgot Password](/images/12-reset-password.png) |


---

## 🛠 Made By  
- [@Prakashsaw](https://github.com/Prakashsaw)  

---

## **📝 License** 
This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this software as long as you include the original license.

---

### **🌟 If you like this project, don't forget to star the repo!** ⭐  
