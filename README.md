# Task Management System

## 📌 Project Description
This is a full-stack **Task Management System** built using:
- **Backend**: Express.js with a SQLite database.
- **Frontend**: React.js for a modern UI.
- **API Documentation**: Swagger for interactive API testing.
- **Security**: API authentication using API keys.

## 🛠 Steps to Run the Project Locally

### **1️⃣ Clone the Repository**
Run:
\\\sh
git clone https://github.com/ybmn1995/Task-Management-System.git
cd task-management-system
\\\

### **2️⃣ Install Dependencies**
Navigate into the **backend** and **frontend** folders and install dependencies:

#### **Backend Setup**
\\\sh
cd backend
npm install
\\\

#### **Frontend Setup**
\\\sh
cd ../frontend
npm install
\\\

### **3️⃣ Set Up Environment Variables**
Create a .env file in **both backend and frontend** directories.

#### **Backend (ackend/.env)**
\\\
API_KEY=my-secure-api-key
PORT=5000
\\\

#### **Frontend (rontend/.env)**
\\\
REACT_APP_API_URL=http://localhost:5000/tasks
REACT_APP_API_KEY=my-secure-api-key
\\\

### **4️⃣ Start the Servers**
Run the following commands in **separate terminals**:

#### **Start Backend**
\\\sh
cd backend
npm start
\\\
This will run the backend at **http://localhost:5000**

#### **Start Frontend**
\\\sh
cd frontend
npm start
\\\
This will run the React app at **http://localhost:3000**

---

## 📌 Assumptions & Decisions Made
1. **API Authentication**: The backend uses an API key system for security.
2. **Database**: The project uses **SQLite** for simplicity.
3. **Deployment Ready**: The structure is built to be deployable to **Vercel/Netlify (frontend)** and **Render/Heroku (backend)**.

---

## 📌 GitHub Repository
🔗 **[GitHub Repository](https://github.com/ybmn1995/task-management-system)**

---


---

### 🛠 Created with ❤️ by **Yousof Nabtiti**

