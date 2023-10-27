# Trello Clone

Trello Clone is a web-based project management application built with modern web technologies. It offers an intuitive user interface for managing tasks, collaborating with team members, and organizing projects effectively.

## Features

- **Intuitive User Interface**: User-friendly design for easy task management and navigation.
- **Real-time Updates**: Collaborate in real-time, ensuring everyone stays up-to-date.
- **Task Organization**: Create boards, lists, and cards for efficient task organization.
- **Custom Styling**: Stylish and responsive design with custom CSS for a unique user experience.
- **Local State Management**: Efficient state management using React Hooks and the Context API.
- **Secure User Data**: User details managed through HTTPS REST architecture for data security.
- **Persistent Sessions**: User sessions managed with local storage, ensuring a seamless experience.

## Getting Started

### Prerequisites

- PostgreSQL installed: [Download PostgreSQL](https://www.postgresql.org/download/).
- Clone the repository: `https://github.com/poorvika11/ascend-task`.
- Update PostgreSQL user details in `server/db.js`.
- Install dependencies:
  - Navigate to the `server` directory: `cd server` and run `npm install`.
  - Navigate to the `react-frontend` directory: `cd react-frontend` and run `npm install`.

### Running the Application

1. **Database Setup**:
   - Install PostgreSQL and create a database named "trelloclone".
   - Use the SQL queries in `server/data.sql` to create the necessary tables.

2. **Server and Frontend**:
   - In the `server` directory, run `npm start` to start the API server.
   - In the `react-frontend` directory, run `npm start` to launch the frontend server.

3. **Access**:
   - Frontend: [http://localhost:3000](http://localhost:3000).
   - Express API: [http://localhost:5000](http://localhost:5000).

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for bug fixes, features, or improvements.

## License

This project is licensed under the [MIT License](LICENSE).

