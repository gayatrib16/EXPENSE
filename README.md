# Expense Tracker - MERN Stack

## Overview

This Expense Tracker is a fullstack web application developed using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to manage their incomes and expenses efficiently, offering a user-friendly interface and dynamic functionalities.

## Features

- **Add Incomes and Expenses**: Users can easily add their incomes and expenses. CRUD operations (Create, Read, Update, Delete) are fully implemented for both incomes and expenses.

- **Dashboard & Analytics**: The dashboard provides an overview of financial statistics:
  - **Total Income and Total Expense**: Displays the total income and expenses.
  - **Net Balance**: Calculates the remaining balance by subtracting total expenses from total income.
  - **Min & Max Income/Expense**: Highlights the minimum and maximum values for both income and expenses.
  - **Graphs & Charts**: Visual representation of financial data using Chart.js for better insight and analysis.

## Technologies Used

- **Frontend**: 
  - **React.js**: Used for building the dynamic and interactive user interface.
  - **Chart.js**: Integrated for creating various graphs and charts to visualize income and expense data.
  
- **Backend**:
  - **Node.js & Express.js**: Used to create RESTful APIs and handle the server-side logic.
  - **MongoDB**: A NoSQL database used to store income and expense records.

## Installation & Setup

### Prerequisites

- Node.js (v14+)
- MongoDB (local or Atlas)
- npm (Node Package Manager)

### Steps to Install

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/expense-tracker-mern.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd expense-tracker-mern
    ```
3. **Install Backend Dependencies:**
    ```bash
    cd backend
    npm install
    ```
4. **Install Frontend Dependencies:**
    ```bash
    cd ../frontend
    npm install
    ```

5. **Set Up Environment Variables:**
    Create a `.env` file in the `backend` directory and add the following:

    ```env
    MONGO_URI=your-mongodb-uri
    PORT=5000
    NODE_ENV=development
    ```

6. **Run the Application:**
    - Start the backend server:
        ```bash
        cd backend
        npm start
        ```
    - Start the frontend server:
        ```bash
        cd ../frontend
        npm start
        ```

7. **Access the Application:**
    - Visit `http://localhost:3000` in your browser to view the frontend.
    - The backend server runs on `http://localhost:5000`.

## Usage

- **Add Income/Expense**: Navigate to the "Add Transaction" section, fill in the required details, and submit.
- **View Dashboard**: The dashboard provides a summarized view with graphs and statistics about your financial status.
- **Delete**: You can delete any transaction directly from the list.



