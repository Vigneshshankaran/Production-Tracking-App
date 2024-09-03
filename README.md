
# 📊Production Tracking App

A comprehensive production tracking web application designed to manage and monitor production processes efficiently. Built using the MERN stack (MongoDB, Express, React, Node.js), this app helps administrators track, analyze, and optimize production workflows.

## 📝 Table of Contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)

## 🚀 Features

- Real-time tracking of production processes and workflows.
- Detailed dashboards with charts and analytics for production data.
- User management with role-based access control (RBAC).
- Alerts and notifications for production milestones and issues.
- Export and import production data in various formats (CSV, Excel).
- Responsive design to ensure usability across all devices.
- Secure authentication and authorization.

## 📸 Screenshots

![Home Screen](https://github.com/user-attachments/assets/ecc59cbc-dffe-4d30-9798-0f980b8b9577)
*Home Screen - Overview of production statistics*


> *Add more screenshots with descriptions as needed.*

## 🛠 Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/Production-Tracking-App.git
    cd Production-Tracking-App
    ```

2. **Install dependencies**:

   - For the server:
     ```bash
     cd backend
     npm install
     ```

   - For the client:
     ```bash
     cd ../frontend
     npm install
     ```

3. **Set up environment variables**:

   Create a `.env` file in the `backend` folder and add your environment variables (e.g., MongoDB URI, JWT secret, email service credentials).

4. **Run the app**:

   - Start the backend server:
     ```bash
     cd backend
     npm run dev
     ```

   - Start the frontend development server:
     ```bash
     cd ../frontend
     npm start
     ```

   The app will be running at `http://localhost:3000`.

## 🎮 Usage

- Log in as an admin to access all features.
- Monitor production workflows through the dashboard.
- Manage users, roles, and permissions.
- Export or import production data to analyze offline.
- Set up alerts for production thresholds and monitor notifications.

## 🧰 Technologies Used

- **Frontend**: React, Material-UI (MUI), Axios
- **Backend**: Node.js, Express, MongoDB, Mongoose
- **Authentication**: JWT (JSON Web Tokens), bcrypt
- **Deployment**: Netlify (Frontend), Vercel (Backend)

