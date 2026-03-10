# 📝 To-Do List Application

A comprehensive full-stack To-Do application built with a modern tech stack. This application features role-based access control, task management, and a sleek user interface.

## 🚀 Features

- **User Authentication**: Secure Login and Registration using JWT and bcrypt.
- **Role-Based Access Control**: Different views and permissions for Admins and Employees.
- **Task Management**: Create, read, update, and delete tasks.
- **Responsive Design**: Styled with Tailwind CSS for a seamless experience across devices.
- **Modern UI**: Built with React and powered by Vite for fast development and execution.
- **Persistent Storage**: Utilizes PostgreSQL with Prisma ORM for reliable data management.

## 🛠️ Tech Stack

### Frontend
- **React**: UI library.
- **Vite**: Next-generation frontend tooling.
- **Tailwind CSS**: Utility-first CSS framework.
- **React Router**: Declarative routing.
- **Axios**: Promise-based HTTP client.

### Backend
- **Node.js**: JavaScript runtime.
- **Express**: Fast, unopinionated web framework.
- **Prisma**: Next-generation Node.js and TypeScript ORM.
- **PostgreSQL**: Relational database.
- **JWT**: For secure authentication.

---

## 📂 Project Structure

```text
todo-app/
├── backend/            # Express.js server and Prisma schema
│   ├── prisma/         # Database schema and migrations
│   └── src/            # Backend source code
├── frontend/           # React + Vite application
│   ├── src/            # Frontend source code
│   └── public/         # Static assets
└── README.md           # Main project documentation
```

---

## ⚙️ Getting Started

### Prerequisites
- Node.js (v16 or higher)
- PostgreSQL
- npm or yarn

### 1. Clone the repository
```bash
git clone https://github.com/puneet-art/to-do-list.git
cd to-do-list
```

### 2. Setup Backend
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file and add your `DATABASE_URL`:
   ```bash
   DATABASE_URL="postgresql://user:password@localhost:5432/todo_db"
   JWT_SECRET="your_secret_key"
   ```
4. Run Prisma migrations:
   ```bash
   npx prisma migrate dev
   ```
5. Start the server:
   ```bash
   npm run dev
   ```

### 3. Setup Frontend
1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

---

## 📜 Scripts

### Backend
- `npm run dev`: Starts the server using nodemon.
- `npm start`: Starts the server normally.
- `npm run migrate:deploy`: Deploys migrations.

### Frontend
- `npm run dev`: Starts the Vite development server.
- `npm run build`: Builds the application for production.
- `npm run preview`: Previews the production build.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📄 License

This project is [MIT](https://choosealicense.com/licenses/mit/) licensed.
