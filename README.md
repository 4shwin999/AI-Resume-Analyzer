# 📄 AI Resume Analyzer

An AI-powered Resume Analyzer that evaluates resumes against job descriptions and provides an ATS-style matching score, skill-gap analysis, and personalized improvement suggestions.

## 🚀 Overview

Recruiters often use Applicant Tracking Systems (ATS) to filter resumes before they reach human reviewers. This project helps job seekers understand how well their resumes align with a target job description by analyzing content similarity and identifying missing keywords and skills.

The application allows users to upload a PDF resume, paste a job description, and instantly receive insights about their resume's compatibility with the role.

---

## ✨ Features

- Upload resumes in PDF format
- Extract and process resume text automatically
- Compare resume content with job descriptions
- Generate a Resume Match Score
- Identify matching keywords and skills
- Detect missing skills and keywords
- Provide resume improvement suggestions
- Interactive web interface built with Streamlit

---

## 🛠️ Tech Stack

### Frontend
- Streamlit

### Backend
- Python

### Libraries
- PyPDF2
- Scikit-learn
- Pandas
- NumPy

### Concepts Used
- Natural Language Processing (NLP)
- Text Vectorization
- Cosine Similarity
- Keyword Extraction
- Resume Parsing

---

## 📂 Project Structure

```text
AI-Resume-Analyzer/
│
├── app.py
├── utils.py
├── requirements.txt
├── README.md
│
└── assets/
    └── sample_resume.pdf
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/AI-Resume-Analyzer.git
```

```bash
cd AI-Resume-Analyzer
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

---

## 📊 How It Works

1. User uploads a PDF resume.
2. Resume text is extracted and cleaned.
3. User pastes a target job description.
4. Text is converted into numerical vectors using CountVectorizer.
5. Cosine Similarity is used to calculate the matching score.
6. Matching and missing skills are identified.
7. Results are displayed through an interactive dashboard.

---

## 🎯 Example Workflow

### Input

Resume:
- Python
- SQL
- Machine Learning
- Git

Job Description:
- Python
- SQL
- Machine Learning
- AWS
- Docker

### Output

Resume Match Score: 80%

Matching Skills:
- Python
- SQL
- Machine Learning

Missing Skills:
- AWS
- Docker

---

## 📸 Screenshots

Add screenshots of the application here after deployment.

### Home Page

![Home Page](screenshots/home.png)

### Analysis Results

![Results](screenshots/results.png)

---

## 🔮 Future Improvements

- AI-powered resume feedback using Gemini/OpenAI
- ATS score prediction
- Resume section analysis
- Skill recommendation engine
- PDF report generation
- Multiple resume comparison
- Resume optimization suggestions
- Job recommendation system

---

## 💡 Learning Outcomes

This project helped strengthen understanding of:

- Python Development
- NLP Fundamentals
- Document Processing
- Similarity Analysis
- Machine Learning Basics
- Streamlit Application Development
- Git and GitHub Workflow

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a new branch
3. Make changes
4. Commit your updates
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Ashwin Chandel

B.Tech Computer Science Engineering

Interested in Software Development, AI/ML, and Full-Stack Development.

GitHub: https://github.com/4shwin999
