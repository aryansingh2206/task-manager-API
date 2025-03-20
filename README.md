
### **🚀 Task Manager API**  
A simple yet powerful **Task Manager API** built with **Node.js, Express.js, and MongoDB**. This API allows users to create, update, retrieve, and delete tasks.  

📌 **Tech Stack:**  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose)  
- **Environment Variables:** dotenv  
- **API Security:** CORS  

---

## **📂 Features**  
✅ Create tasks with a title, description, and status (completed/incomplete)  
✅ Fetch all tasks or a single task by ID  
✅ Update task details  
✅ Delete tasks  
✅ RESTful API design  
✅ Uses MongoDB for persistent storage  

---

## **🛠️ Installation & Setup**  

### **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/aryansingh2206/task-manager-API.git
cd task-manager-API
```

### **2️⃣ Install Dependencies**  
```sh
npm install
```

### **3️⃣ Set Up Environment Variables**  
Create a `.env` file in the project root and add the following:  
```
MONGO_URI=mongodb://localhost:27017/taskmanager
PORT=5000
```

### **4️⃣ Start the Server**  
```sh
npm run dev
```
If successful, you should see:  
```
🚀 Server running on port 5000
✅ MongoDB Connected
```

---

## **📌 API Endpoints**  

### **📍 Create a Task**  
🔹 **POST** `/api/tasks`  
```json
{
  "title": "Complete Node.js project",
  "description": "Build a Task Manager API",
  "completed": false
}
```

### **📍 Get All Tasks**  
🔹 **GET** `/api/tasks`

### **📍 Get Task by ID**  
🔹 **GET** `/api/tasks/:id`

### **📍 Update Task**  
🔹 **PUT** `/api/tasks/:id`  
```json
{
  "title": "Update Project",
  "completed": true
}
```

### **📍 Delete Task**  
🔹 **DELETE** `/api/tasks/:id`  

---

## **🛠️ Technologies Used**  
- **Express.js** – Web framework for Node.js  
- **MongoDB & Mongoose** – NoSQL database and ODM  
- **Nodemon** – Auto-restarts server during development  
- **dotenv** – Manage environment variables  
- **CORS** – Enable cross-origin requests  

---

## **📢 Contributing**  
Contributions are welcome! To contribute:  
1. Fork the repo  
2. Create a new branch: `git checkout -b feature-name`  
3. Commit changes: `git commit -m "Added new feature"`  
4. Push to the branch: `git push origin feature-name`  
5. Open a **Pull Request**  

---

## **💡 Future Improvements**  
🔹 User authentication with JWT  
🔹 Task categories and priority levels  
🔹 API documentation with Swagger  

---

**💙 Made with Node.js, Express, and MongoDB** 🚀  
