📌 Task Management System
🚀 Project Overview
The Task Management System is a full-stack web application designed for efficiently managing tasks. It features a modern UX/UI and is built with:
🔹 Backend:
- Express.js + SQLite (Node.js)
- API authentication using an API key
- Swagger for interactive API documentation
- Deployed on Render (Auto-deploys on Git push)
🔹 Frontend:
- React.js with Vercel deployment
- Responsive design (Optimized for mobile & desktop)
- Environment variables for API configuration
- Modern UX/UI (Simple, intuitive, and user-friendly)
🌍 Live Demo
🔗 Live App: https://task-management-system-wine-mu.vercel.app/
🔗 Swagger API Docs: https://task-management-system-kwt1.onrender.com/swagger/
🛠 Steps to Run the Project Locally
1️⃣ Clone the Repository
git clone https://github.com/ybmn1995/task-management-system.git
cd task-management-system
2️⃣ Install Dependencies
Navigate into the backend and frontend folders and install dependencies.
🔹 Backend Setup
cd backend
npm install
🔹 Frontend Setup
cd ../frontend
npm install
3️⃣ Set Up Environment Variables
Create a .env file in both backend and frontend directories.
🔹 Backend (backend/.env)
API_KEY=my-secure-api-key
PORT=5000
🔹 Frontend (frontend/.env)
REACT_APP_API_URL=https://task-management-system-kwt1.onrender.com
REACT_APP_API_KEY=my-secure-api-key
4️⃣ Start the Servers
🔹 Start Backend
cd backend
npm start
Backend will run at: http://localhost:5000
🔹 Start Frontend
cd frontend
npm start
Frontend will run at: http://localhost:3000
📌 Features
🔹 Backend (Node.js + Express)
✅ Task Management API with CRUD operations:
- GET /tasks → Fetch all tasks
- POST /tasks → Create a new task
- PUT /tasks/:id → Update an existing task
- DELETE /tasks/:id → Delete a task
✅ Authentication & Security: API Key authentication
✅ Database Integration: Uses SQLite3 (Can be upgraded to PostgreSQL for production)
✅ Validation & Clean Code: Input validation & modularized structure
✅ Swagger API Documentation: Available at Swagger Docs
✅ Environment Variables (.env) for security
✅ Deployed on Render: Auto-deploys on Git push
🔹 Frontend (React + Vercel)
✅ Modern UX/UI with a responsive design
✅ Connects with backend API using fetch()
✅ Environment Variables (.env) for API configuration
✅ Deployed on Vercel with automatic GitHub deployment
📌 Deployment Details
🔗 GitHub Repository: https://github.com/ybmn1995/task-management-system
🔗 Backend API on Render: https://task-management-system-kwt1.onrender.com/swagger/
🔗 Frontend on Vercel: https://task-management-system-wine-mu.vercel.app/
🛠 Additional Step for Local Setup
Update `package.json` in the frontend directory to include:
"scripts": {
  "start": "set NODE_OPTIONS=--openssl-legacy-provider && react-scripts start",
  "build": "set NODE_OPTIONS=--openssl-legacy-provider && react-scripts build"
}
🛠 Created with ❤️ by Yousef Nabtiti
