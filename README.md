# User-Authentication-System

# Signup Page
![Screenshot (526)](https://github.com/user-attachments/assets/3d823e02-f4da-4d07-8589-2991d0b25417)

# Validations
![Screenshot (527)](https://github.com/user-attachments/assets/74654514-e8ba-4f15-987c-1058a1b8309c)

# Signup
![Screenshot (528)](https://github.com/user-attachments/assets/655e744c-de4d-4591-96fb-dd99661e8fd3)



# Login Page
![Screenshot (522)](https://github.com/user-attachments/assets/dad5c158-8d4f-4d84-9e9e-cd1a95e1c069)

![Screenshot (521)](https://github.com/user-attachments/assets/9ddd0639-78a3-4c4e-b741-0477e013169f)

# Logout Page
![Screenshot (524)](https://github.com/user-attachments/assets/dca7e777-09dc-401a-acd3-9ea7ee637971)

### User Authentication System: MERN Stack Challenge

---

### 📁 Project Overview
I developed a user authentication system using the MERN stack. The module allows users to register, log in, view a protected profile page, and log out. The project ensures secure handling of user data with responsive front-end forms and secure back-end API routes.

---

### 🎯 Key Features

1. **User Registration:** 
   - Users can register with a username, email, and password. 
   - Passwords are securely hashed using `bcrypt`.
  
2. **User Login:** 
   - Users log in using their email and password.
   - `JWT` is used for session management.
  
3. **Profile Page:** 
   - Displays username and email. 
   - Accessible only to logged-in users.
  
4. **Logout Functionality:** 
   - Ends the user session by removing the JWT token.
  
5. **Frontend:** 
   - Built with React.js. 
   - Responsive forms and routing with React Router.
  
6. **Backend:** 
   - API built with Node.js and Express.js.
   - MongoDB with Mongoose for data storage.
   - Secured routes using JWT middleware.
  
7. **Error Handling:** 
   - Proper error handling and display on both frontend and backend.

---

### 🛠️ **Setup Instructions**

#### **Frontend Setup:**
1. Navigate to the `frontend` directory and install dependencies:
   ```bash
   npm install
   ```
2. Start the React development server:
   ```bash
   npm start
   ```
3. Access at [http://localhost:3000](http://localhost:3000).

#### **Backend Setup:**
1. Navigate to the `backend` directory and install dependencies:
   ```bash
   npm install
   ```
2. Create a `.env` file with:
   ```plaintext
   PORT=8080
   JWT_SECRET=your_jwt_secret
   MONGODB_URI=your_mongodb_connection_string
   ```
3. Start the Express server:
   ```bash
   npm start
   ```

---

### 🔑 **Project Structure**

- **Frontend:** React components, pages, and utilities are organized for clean code and reusability.
- **Backend:** API routes, controllers, and middleware are structured for secure and efficient operations.

---

