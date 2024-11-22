

# Expense Tracker

## Description

Expense Tracker is a full-stack web application built using the **MERN** stack (MongoDB, Express, React, Node.js) to help users track their daily expenses. The application allows users to record, categorize, and analyze their expenses with the ability to filter by date and category. The app also supports data export to Excel and PDF for easier tracking and reporting.

This project is designed to help individuals keep an eye on their spending habits and manage their budget effectively.

## Key Features

- **User Authentication**: Sign up and log in using JWT authentication.
- **Expense Management**: Add, edit, and delete expenses.
- **Categories**: Organize expenses by categories such as food, transportation, bills, etc.
- **Expense Filtering**: Filter expenses by date and category.
- **Data Visualization**: View expense trends with graphical charts.
- **Export Options**: Download the expense data as a PDF or Excel file.
- **Responsive Design**: Mobile-friendly interface.

## Technologies Used

- **Frontend**:
  - React.js
  - React Router
  - Chart.js (for graphical representation of expenses)
  - Axios (for making API requests)

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB
  - JSON Web Tokens (JWT) for user authentication
  - Multer (for file upload functionality)

- **Tools & Libraries**:
  - Bootstrap (for responsive design)
  - React-Bootstrap (UI components)
  - React-Chartjs-2 (for integrating charts)
  - pdfkit (for PDF export)
  - exceljs (for Excel export)

## Installation Instructions

Follow these steps to set up the project locally:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd expense-tracker
   ```

3. Install backend dependencies:
   ```bash
   cd backend
   npm install
   ```

4. Install frontend dependencies:
   ```bash
   cd frontend
   npm install
   ```

5. Create a `.env` file in the **backend** directory and add the following environment variables:
   ```env
   MONGO_URI=your_mongodb_connection_string
  
   ```

6. Run the server:
   ```bash
   cd backend
   npm start
   ```

7. Run the frontend:
   ```bash
   cd frontend
   npm start
   ```

8. The application should now be running locally on `http://localhost:3000`.

## Usage

- **User Registration**: Sign up with your email and create a password. An OTP will be sent to your email for verification.
- **Adding Expenses**: Once logged in, click on "Add Expense" to record an expense with details like the amount, category, and date.
- **Filtering Expenses**: Use the date and category filters to narrow down your expenses.
- **Exporting Data**: Download your expenses as a PDF or Excel file by using the "Export" button on the dashboard.
- **View Charts**: View your expenses in a graphical format on the dashboard.

## Dependencies

- **Backend Dependencies**:
  - express
  - mongoose
  - bcryptjs
  - multer
  - nodemailer
  - dotenv

- **Frontend Dependencies**:
  - react
  - react-dom
  - react-router-dom
  - axios
  - chart.js
  - react-chartjs-2
  - bootstrap
  - react-bootstrap

## Motivation

The motivation behind creating this project was to help users keep track of their daily expenses efficiently. By providing an intuitive interface and data analysis features, the application empowers individuals to manage their finances and make informed budgeting decisions.

## Contact

- **Developer**: Tharun
- **Email**: [tharunkudiyala.com](mailto:tharunkudikyala@gmail.com)
- **GitHub**: [tharun2107](https://github.com/tharun2107)

---

Thank you for checking out this project! Feel free to contribute, raise issues, or provide feedback.
```

### Explanation of Sections:
- **Description**: Describes the purpose and goals of the project.
- **Key Features**: Lists the features and functionality that the application provides.
- **Technologies Used**: Specifies the tech stack used in the project (Frontend and Backend).
- **Installation Instructions**: Provides a step-by-step guide to setting up the project on a local machine.
- **Usage**: Provides guidance on how to use the project once it's set up.
- **Dependencies**: Lists the major libraries and dependencies used.
- **Motivation**: Briefly explains why the project was created.
- **Contact**: Provides the developer's contact information.

