```markdown
# 🧠 AI Resume Screening System

An intelligent and modern web application that uses AI to automate the process of screening student resumes. The system compares resumes against job requirements provided by recruiters and highlights the most suitable candidates — streamlining hiring, saving time, and enhancing accuracy.


## 🌟 Features

- ✅ Clean & modern UI with Light/Dark mode support
- ✅ Separate dashboards for Students and Recruiters
- ✅ Resume upload in `.docx` format with AI parsing (OpenAI API)
- ✅ Recruiters can create, view, and manage job listings
- ✅ Students can apply for jobs and update profiles anytime
- ✅ Smart filtering and matching of resumes based on required skills
- ✅ Live updates of applied and selected students for each job
- ✅ Secure authentication system
- ✅ SQLite database for local development


## 🖼️ Screenshots

*(Add screenshots here later to show off the Home Page, Dashboards, Job Tables, etc.)*


## 🧪 Tech Stack

| Technology   | Purpose                   |
|--------------|----------------------------|
| React        | Frontend UI                |
| Tailwind CSS | Styling                    |
| Node.js      | Backend logic              |
| Express.js   | API creation               |
| SQLite       | Local database             |
| OpenAI API   | Resume parsing & screening |
| Git/GitHub   | Version control            |


## 🚀 How to Run This Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/ai-resume-screening.git
cd ai-resume-screening
```

### 2. Install Dependencies

#### For Backend
```bash
cd backend
npm install
```

#### For Frontend
```bash
cd ../frontend
npm install
```

### 3. Setup OpenAI API

- Create a `.env` file inside `backend/` and add your OpenAI key:

```
OPENAI_API_KEY=your_openai_api_key_here
```

### 4. Run the Project

#### Start Backend
```bash
cd backend
npm start
```

#### Start Frontend
```bash
cd ../frontend
npm run dev
```

Project will run at `http://localhost:5173`

---

## 📂 Project Structure

```
ai-resume-screening/
│
├── frontend/             # React + Tailwind frontend
│   └── ...               
│
├── backend/              # Node.js + Express backend
│   └── ...              
│
├── database/             # SQLite database setup
│   └── resumeDB.sqlite
│
└── README.md
```

---

## 🧠 AI Logic (Simplified)

1. Student uploads `.docx` resume.
2. OpenAI API parses and extracts key skills from resume.
3. When student applies to a job, AI matches resume skills with job’s required skills.
4. If match is strong, student is added to "Selected Students" for that job listing.

---

## 🤝 Contributing

We welcome contributions from everyone! 🚀

### How to Contribute:
1. **Fork** this repo
2. **Clone** your forked copy
3. Create a **new branch**: `git checkout -b feature-xyz`
4. Make your changes and **commit**: `git commit -m "Added something"`
5. **Push** to your fork: `git push origin feature-xyz`
6. Open a **Pull Request** and wait for review

---

## 📜 License

This project is open-source and free to use under the GNU 3 License.

---

## © 2025 YashGargDev | Dhruv Gupta | Ritesh Kumar Sinha | Apurva Bansal

```
