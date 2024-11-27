Here’s a simplified version of the **README.md** file with only the **features** and **how to run** sections:

---

## 🍳 LMS Project

### Features
- **User Authentication**: Register, log in, change password, and reset password via email.
- **User Profile**: Edit and view profile details.
- **Course Management**: Admin can create, edit, and delete courses.
- **Lecture Management**: Admin can add, edit, and delete lectures.
- **Subscription**: Users can enroll in courses by purchasing a 1-year subscription.
- **Lecture Dashboard**: Display lectures, play videos, and view lecture descriptions.
- **Admin Dashboard**: Admin can manage users, courses, and payments.
- **Email Notifications**: Automated emails for actions like course enrollment and password reset.
- **Subscription Verification**: Admin can verify and cancel subscriptions.

---

### How to Run

#### 1. Clone the Repository:
   ```bash
   git clone https://github.com/Ameet407/LMS_mern.git
   cd LMS
   ```

#### 2. Set Up the Backend:
   - Navigate to the `backend` folder:
     ```bash
     cd backend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Set up environment variables by creating a `.env` file (use `.env.example.js` as reference).
   - Start the backend server:
     ```bash
     npm start
     ```

#### 3. Set Up the Frontend:
   - Navigate to the `client` folder:
     ```bash
     cd client
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Set up environment variables by creating a `.env` file (use `.env.example.js` as reference).
   - Start the frontend development server:
     ```bash
     npm run dev
     ```

#### 4. Access the Application:
   Open your browser and visit: `http://localhost:5173`

---

This version focuses on the core features of the project and the steps to set it up and run locally.