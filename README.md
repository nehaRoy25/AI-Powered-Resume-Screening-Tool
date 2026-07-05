# 🚀 AI Resume Screening Tool

An intelligent web application that streamlines the resume screening process using Artificial Intelligence and Natural Language Processing (NLP). It helps recruiters quickly identify the most relevant candidates by comparing resumes against job requirements.

---

## 📌 Project Overview

Hiring teams often spend hours reviewing resumes manually. This application automates that process by extracting resume content, comparing it with a job description, checking for required skills, and generating AI-based recommendations.

The system uses the **Groq API** to understand resume content and provide meaningful feedback instead of relying only on keyword matching.

---

## ✨ Key Features

* 📄 Upload one or multiple PDF resumes at once.
* 📝 Enter a job description for the target role.
* 🔍 Specify required or mandatory skills.
* 🤖 AI-powered resume evaluation using the Groq API.
* 📊 Candidate classification into:

  * ✅ Suitable
  * ⚠️ Maybe Suitable
  * ❌ Not Suitable
* 💬 Detailed AI-generated reasoning for every decision.
* 📁 Export screening results as a CSV file.
* ⚡ Fast and user-friendly web interface.

---

## 🖼️ Application Preview

### Resume Upload

Upload multiple resumes through the web interface.

![Upload Interface](/Image%20file/Interface1.png)

### Screening Results

View AI-generated evaluations with classifications and detailed comments.

![Results](/Image%20file/result%20interface.png)

---

## ⚙️ Workflow

1. Upload one or more PDF resumes.
2. Enter the job description.
3. Add mandatory skills or keywords.
4. Click **Submit**.
5. The application extracts resume text using **pdfplumber**.
6. The Groq AI model analyzes each resume against the job requirements.
7. Review the generated suitability score and feedback.
8. Download the results in CSV format if needed.

---

## 🛠️ Technology Stack

| Component      | Technology            |
| -------------- | --------------------- |
| Backend        | Flask (Python)        |
| Frontend       | HTML, CSS, JavaScript |
| AI Engine      | Groq API              |
| PDF Processing | pdfplumber            |
| Data Export    | CSV                   |

---

## 📥 Installation

### Clone the repository

```bash
git clone https://github.com/username/ai-resume-screening-tool.git
cd ai-resume-screening-tool
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Configure Flask

**Windows**

```bash
set FLASK_APP=app.py
```

**Linux/macOS**

```bash
export FLASK_APP=app.py
```

### Run the application

```bash
flask run
```

The application will be available locally in your browser.

---

## 🚀 How to Use

1. Launch the Flask application.
2. Open the web interface.
3. Upload one or more PDF resumes.
4. Provide the job description.
5. Enter required skills or keywords.
6. Submit the form.
7. Review the AI-generated candidate analysis.
8. Export the results as a CSV file if desired.

---

## 📂 Project Highlights

* Automated resume parsing
* AI-driven candidate evaluation
* Intelligent skill matching
* Recruiter-friendly interface
* Multiple resume support
* Downloadable screening reports

---

## 🤝 Contributing

Contributions are always welcome!

1. Fork this repository.
2. Create a new feature branch.

```bash
git checkout -b feature/new-feature
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push your branch.

```bash
git push origin feature/new-feature
```

5. Open a Pull Request for review.

---

## 📜 License

This project is distributed under the **MIT License**.

See the **LICENSE** file for complete licensing information.
