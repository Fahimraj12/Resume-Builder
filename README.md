# Resume-Builder
- This is a Resume Builder web application built using the **MERN (MongoDB, Express.js, React.js, Node.js) stack**.  
- It allows users to create, edit, and manage resumes online with a clean and responsive interface.

- Users can register, log in securely, and save their resume data for future editing. The backend stores data in MongoDB, and the frontend provides a smooth user experience on both desktop and mobile devices.

- This repository contains the **frontend (`client/`) and backend (`server/`) code** for the project.

---

## Features
1. User authentication (register, login, logout)  
2. Create, update, and delete resume sections  
3. Responsive design for mobile and desktop  
4. Secure data storage using MongoDB  
5. Download resume as PDF  
6. Multiple professional resume templates  


---

## Tech Stack

| Category | Technologies Used |
|-----------|-------------------|
| **Frontend** | React.js, Redux Toolkit, Tailwind CSS, Material UI |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (Mongoose ORM) |
| **Authentication** | JWT (JSON Web Tokens) |
| **Resume Export** | jsPDF |
| **Version Control** | Git, GitHub |

---

## ⚙️ Installation & Setup

### Prerequisites
- Node.js (v16+)
- MongoDB (local or Atlas)
- Git

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Fahimraj12/Resume-Builder.git
   cd resume-builder

2. **Install dependencies**
   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install

3. **Set up environment variables**
- Create a .env file inside the backend directory:
   ```bash
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key

4. **Run the app**
- Backend:
   ```bash
   cd backend
   npm start
- Frontend:
  ```bash
  cd frontend
  npm start

### 👨‍💻 Author
- [Mo Fahim Raj](https://www.linkedin.com/in/mo-fahim-raj-175b9b304/)
- 📧 [mofahimraj@gmail.com]
- 🔗 [GitHub Profile](https://github.com/Fahimraj12)
