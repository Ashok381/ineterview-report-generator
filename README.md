# 🤖 IntervyAI

**IntervyAI** is an AI-powered interview preparation platform that helps job seekers evaluate their readiness for a specific role. Simply upload your resume, paste a job description, and provide a short self-description. The application analyzes your profile using AI and generates a comprehensive interview report along with a personalized preparation plan.

---

## ✨ Features

* 📄 Upload Resume (PDF)
* 💼 Analyze Resume Against a Job Description
* 🧠 AI-Generated Interview Report
* 📊 Match Score Between Candidate and Job Description
* 💻 Technical Interview Questions
* 🗣️ Behavioral Interview Questions
* 🎯 Skill Gap Analysis
* 📅 Personalized Multi-Day Preparation Plan
* 📥 AI-Generated Resume Download
* 🔐 Secure User Authentication (JWT + Cookies)
* 📚 Dashboard to View Previous Reports

---

## 🖼️ Screenshots

> Add screenshots of your application here.

```
/screenshots
    ├── Home.png
    ├── Dashboard.png
    ├── Report.png
```

---

# 🛠️ Tech Stack

## Frontend

* React.js
* React Hook Form
* HTML5
* CSS3
* JavaScript (ES6+)

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Multer
* PDF Parser

## AI

* Google Gemini API

---

# 📂 Project Structure

```
IntervyAI
│
├── frontend
│   ├── src
│   ├── public
│   └── package.json
│
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   ├── services
│   ├── utils
│   ├── schemas
│   └── package.json
│
└── README.md
```

---

# 🚀 Getting Started

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/IntervyAI.git
cd IntervyAI
```

---

## 2. Install Dependencies

### Backend

```bash
cd backend
npm install
```

### Frontend

```bash
cd frontend
npm install
```

---

## 3. Environment Variables

Create a `.env` file inside the backend directory.

Example:

```env
PORT=3000

MONGODB_URI=your_mongodb_connection_string

ACCESS_TOKEN_SECRET=your_access_secret

ACCESS_TOKEN_EXPIRY=1d

REFRESH_TOKEN_SECRET=your_refresh_secret

REFRESH_TOKEN_EXPIRY=7d

GEMINI_API_KEY=your_google_gemini_api_key

CORS_ORIGIN=http://localhost:5173
```

---

## 4. Run the Backend

```bash
npm run dev
```

---

## 5. Run the Frontend

```bash
npm run dev
```

The frontend will run on:

```
http://localhost:5173
```

The backend will run on:

```
http://localhost:3000
```

---

# 🔑 Authentication

The application uses:

* JWT Access Token
* Refresh Token
* HTTP-Only Cookies
* Protected Routes

---

# 📄 AI Report Includes

After uploading a resume, the AI generates:

* Match Score
* Technical Questions
* Behavioral Questions
* Suggested Answers
* Skill Gap Analysis
* Personalized Preparation Plan

---

# 📥 Resume Generator

IntervyAI can also generate an improved resume based on:

* Uploaded Resume
* Job Description
* Candidate Profile

The generated resume can be downloaded as a PDF.

---

# 📌 API Endpoints

## Authentication

```
POST /api/user/register

POST /api/user/login

POST /api/user/logout

POST /api/user/refresh-token
```

---

## Interview

```
POST /api/interview/get-interviewReport

POST /api/interview/generate-resume

POST /api/interview/get-AllgeneratedReport
```

---

# 📈 Future Improvements

* AI Mock Interview
* Voice-Based Interview Practice
* ATS Resume Score
* Company-Specific Interview Questions
* Resume Version History
* Dark Mode
* Interview Progress Tracker
* Email Report Sharing

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Ashok Samrat**

If you found this project useful, consider giving it a ⭐ on GitHub.
