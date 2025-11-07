l# Resume-Builder
A modern **Resume Builder Web Application** that allows users to easily create, customize, and download professional resumes.  
Built with **React.js, Redux Toolkit, Node.js, Express, and MongoDB**, this project focuses on a smooth user experience, responsive design, and export-ready resume templates.

---

## 🚀 Features

- 📝 **Dynamic Resume Sections**
  - Add, edit, or delete Education, Experience, Projects, and Skills dynamically.
- 🧩 **Multiple Templates**
  - Choose from pre-designed templates and customize colors, layout, and font styles.
- 💾 **Save and Edit**
  - Save your progress and continue editing anytime.
- 📤 **Export Options**
  - Download your resume as **PDF** or **Word (DOCX)** format.
- 🔐 **User Authentication**
  - Secure login and registration using JWT.
- ⚡ **State Management**
  - Efficient data handling via **Redux Toolkit**.
- ☁️ **Cloud Database**
  - All user data and templates stored securely in **MongoDB Atlas**.
- 🧠 **Smart Resume Analyzer (Optional)**
  - Analyze resumes using **NLP and ML** to improve professional score (future enhancement).

---

## 🏗️ Tech Stack

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

3. **Run the app**
- Backend:
   ```bash
   cd backend
   npm start
- Frontend:
  ```bash
  cd frontend
  npm start
