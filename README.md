# MERN Stack Employee Management System
## Overview
This project is an Employee Management System built using the MERN stack (MongoDB, Express.js, React, Node.js). This project has the following Modules:
   - **Authentication:** Manages user login, logout, and role-based access.
   - **Dashboard:** Displays statistics and navigation for admin and employees.
   - **Employee Management:** Allows the admin to add, edit, and manage employees.
   - **Department Management:** Manages departments and assigns employees to them.
   - **Leave Management:** Handles employee leave requests and admin approvals.
   - **Salary Management:** Manages employee salary records.
   - **Attendance Management:** Manages employee attendance.
   - **Settings:** Allows users to manage their profile and password.
   - **Utilities:** Handles reusable components like private routes and role-based access.


## Installation
To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone [url of this repository]
   cd [projec]
   ```

2. **Install dependencies for both frontend and backend:**
   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd frontend
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the `backend` directory and add the following:
   ```env
   PORT=[Your Port]
   MONGODB_URL=[Connection URL]
   JWT_SECRET=[Your Secret Key]
   ```

4. **Run the application:**
   ```bash
   # Start the backend server
   cd backend
   npm start

   # Start the frontend server
   cd frontend
   npm run dev
   ```

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this template to better fit your project. Let me know if you need any more help!

