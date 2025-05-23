# 🎓 EduTutor AI

**EduTutor AI** is an AI-powered educational platform that allows both teachers and students to engage with learning materials in a personalized and interactive way. Built with **Streamlit** and **OpenRouter’s AI**, it provides tools for content simplification, quiz generation, and Q&A — all tailored to enhance learning.

## 📌 Features

### 👩‍🏫 For Teachers
- Upload or paste content (PDF/DOCX supported)
- Generate simplified, student-friendly versions
- Create multiple-choice quizzes from your content
- Preview and review AI-generated resources

### 🎓 For Students
- Upload or paste study material
- Receive simplified explanations
- Automatically generate self-assessment quizzes
- Ask AI follow-up questions
- Receive instant quiz results with feedback

## 📂 Project Structure

```
EduTutorAI/
├── app.py               # Main Streamlit app interface
├── api_service.py       # Handles API communication with OpenRouter
├── role_handler.py      # Optional UI for switching roles
├── utils.py             # Core functions: text extraction, quiz generation, grading, etc.
├── requirements.txt     # Project dependencies
└── .env                 # API keys (excluded from version control)
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/EduTutorAI.git
cd EduTutorAI
```

### 2. Create a virtual environment and install dependencies

```bash
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Set up your API key

Create a `.env` file in the project root and add your OpenRouter API key:

```env
API_KEY=your_openrouter_api_key_here
```

## 🚀 Running the Application

To launch the application in your browser:

```bash
streamlit run app.py
```

Then open [http://localhost:8501](http://localhost:8501) in your browser if it doesn’t open automatically.

## 🧠 Powered By

- [OpenRouter API](https://openrouter.ai/) – AI generation
- [Streamlit](https://streamlit.io/) – UI framework
- [pdfplumber](https://github.com/jsvine/pdfplumber) – PDF text extraction
- [python-docx](https://python-docx.readthedocs.io/) – DOCX file processing

## 🛡️ Security Note

- **Do not share your `.env` file or API key publicly.**
- Ensure `.env` is excluded from version control by adding the following line to `.gitignore`:

```
.env
```

## 🙋‍♀️ Contributing

Contributions and suggestions are welcome! Please open an issue or a pull request to get started.

## 👥 Collaborators

This project was created by **Team Risers**.

### Team Members:
- [Abhinay Reddy Kothapally](https://github.com/abhinay6227)
- [Krishnakumar Tulasi](https://github.com/tualsikrishnakumar)
- [Thilak Adepu](https://github.com/thilakadepu)
