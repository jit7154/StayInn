# StayInn

This is a full-stack hotel booking web application designed to provide a seamless reservation experience for users and robust management capabilities for administrators. It features secure **Role-Based Access Control (RBAC)** and advanced data querying using **MongoDB Aggregation Pipelines**.

---

## Features

- **User Authentication:** Secure sign-up, login, and authorization with Role-Based Access Control (RBAC).
- **Comprehensive Booking System:** Streamlined search, filtering, and reservation process for hotel accommodations.
- **Advanced Data Processing:** Leverages MongoDB Aggregation Pipelines for highly efficient data querying, filtering, and property analytics.
- **Admin Management:** Dedicated routes and permissions for administrators to manage properties and users.
- **Responsive Design:** Interactive and dynamic frontend built for a seamless experience across desktop and mobile devices.

---

## Tech Stack

**Frontend:**
- React.js

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose ODM)

---

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js 
- MongoDB (local instance or MongoDB Atlas cluster)
- npm or Yarn
- Git

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/jit7154/StayInn.git](https://github.com/jit7154/StayInn.git)
    cd StayInn
    ```

2.  **Backend Setup:**
    ```bash
    cd server
    npm install
    ```
    Create a `.env` file in the `server` directory and add your environment variables:
    ```
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    ```

3.  **Frontend Setup:**
    ```bash
    cd ../client
    npm install
    ```

---

## Running the Application

1.  **Start the Backend Server:**
    ```bash
    cd server
    npm run dev
    ```

2.  **Start the Frontend Development Server:**
    ```bash
    cd ../client
    npm start
    ```

The application should now be running. Open your browser and navigate to `http://localhost:3000` (or the respective port your frontend is running on).

---

## Usage

1.  **Register a New Account:** Sign up as a user or log in with administrator credentials.
2.  **Browse Properties:** Search and filter through available hotel accommodations.
3.  **Make a Reservation:** Select your dates and complete the booking process.
4.  **Manage Bookings (Admin):** Users with admin access can monitor reservations and manage hotel listings.
