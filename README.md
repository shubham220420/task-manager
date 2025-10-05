# TaskFyer

A full-stack task management application built with Next.js and Node.js, designed to help users organize and track their tasks efficiently.

## Features

- **User Authentication**: Secure login and registration with email verification
- **Task Management**: Create, read, update, and delete tasks
- **Task Filtering**: Filter tasks by status (pending, completed, overdue)
- **Password Recovery**: Forgot password functionality with email reset
- **Responsive Design**: Mobile-friendly interface built with Tailwind CSS
- **Real-time Updates**: Context-based state management for seamless user experience

## Tech Stack

### Frontend
- Next.js
- TypeScript
- Tailwind CSS
- React Context API

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Nodemailer for email services

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd taskfyer
   ```

2. Install backend dependencies:
   ```bash
   cd backend
   npm install
   ```

3. Install frontend dependencies:
   ```bash
   cd ../client
   npm install
   ```

4. Set up environment variables (see Environment Variables section below)

5. Start the MongoDB server (if running locally)

## Usage

1. Start the backend server:
   ```bash
   cd backend
   npm start
   ```

2. Start the frontend development server:
   ```bash
   cd client
   npm run dev
   ```

3. Open your browser and navigate to `http://localhost:3000`

## Environment Variables

Create a `.env` file in the `backend` directory and add the following variables:

- `MONGO_URI=your_mongo_uri`
- `JWT_SECRET=secret or anything random`
- `CLIENT_URL=http://localhost:3000 or any localhost port that you are using`
- `PORT=8000`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
