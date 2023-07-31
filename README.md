# Attendance Management System Documentation

This project is an attendance management system developed using Vite, TypeScript, and React for the frontend, and Node.js, Express, and PostgreSQL for the backend. The system allows teachers to manage student attendance efficiently and enables students to mark their attendance seamlessly.

## Features

- **Teacher Dashboard**: Authenticated teachers can access the dashboard, where they can view attendance reports, manage student records, and generate QR codes for each session.

- **Student Attendance**: Students can scan the QR code generated by the teacher for the current session, which redirects them to the attendance form. After filling in their details, students can mark their attendance.

## Installation

1. Clone the repository to your local machine.
2. Install frontend dependencies:

```bash
cd client
npm install
```

3. Install backend dependencies:

```bash
cd server
npm install
```

4. Start the frontend development server:

```bash
cd client
npm run dev
```

5. Start the backend server:

```bash
cd start
npm run dev
```

## Technologies Used

- **Vite**: A build tool that provides fast and efficient development and building experience for modern web projects.
- **TypeScript**: A statically typed superset of JavaScript that enhances code quality and developer productivity.
- **React**: A popular JavaScript library for building user interfaces using reusable components.
- **Node.js**: A runtime environment for executing JavaScript code on the server side.
- **Express**: A fast and minimalist web framework for building backend applications.
- **PostgreSQL**: A powerful open-source relational database used to store teacher and student information.

## Database Setup

1. Install PostgreSQL on your system.
2. Create a new database named `attendance_db`.
3. Update the database configuration in the backend's `.env` file.

## Getting Started

1. Navigate to the application's URL to access the login page.
2. Log in as a teacher using the provided credentials to access the dashboard.
3. Generate a unique QR code for each attendance session from the dashboard.
4. Students can scan the QR code to access the attendance form and mark their attendance.

## Contributions

Contributions to this project are welcome. If you encounter any bugs or have suggestions for enhancements, feel free to create an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as per your requirements.

We hope you find this attendance management system useful and easy to integrate into your educational institution! Happy coding!
