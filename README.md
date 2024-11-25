# Task-Management-Application
 
A **Task Management Application** designed to help users organize and prioritize their tasks efficiently. This application offers features to add, update, delete, and manage tasks, providing a seamless experience for personal or team productivity.  

## Features  

- **Add Tasks:** Easily create new tasks with essential details like title, description, and due date.  
- **Edit Tasks:** Update task details to keep them relevant and accurate.  
- **Delete Tasks:** Remove completed or unnecessary tasks from the list.  
- **Task Status Tracking:** Mark tasks as pending, in progress, or completed for better task management.  
- **User-Friendly Interface:** Simple and intuitive design for easy navigation.  

## 🛠️ Technologies Used  

- **Frontend:** [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML), [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS), [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)  
- **Backend:** [Node.js](https://nodejs.org/), [Express.js](https://expressjs.com/)  
- **Database:** [MongoDB](https://www.mongodb.com/)  
- **Version Control:** [Git](https://git-scm.com/), [GitHub](https://github.com/)  

## Installation  

Follow these steps to set up and run the project locally:  

1. **Clone the repository:**  
   ```bash  
   git clone https://github.com/noor2560/Task-Management-Application.git  
   cd Task-Management-Application  
   ```  

2. **Install dependencies:**  
   ```bash  
   npm install  
   ```  

3. **Set up the database:**  
   - Ensure you have MongoDB installed and running on your system.  
   - Configure the database connection string in the `.env` file.  

4. **Start the application:**  
   ```bash  
   npm start  
   ```  

5. **Open in browser:**  
   Navigate to `http://localhost:3000` to access the application.  

## Project Structure  

```
Task-Management-Application/  
│  
├── public/              # Static files (CSS, JS, images)  
├── views/               # Frontend templates (EJS files)  
├── routes/              # Application routes  
├── models/              # Database models (Mongoose schemas)  
├── controllers/         # Logic for handling requests  
├── app.js               # Main application file  
└── package.json         # Project configuration and dependencies  
```  

