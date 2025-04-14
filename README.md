# SmartATS Reviewer: Gemini LLM Powered Resume Analyzer ✨

An AI-Powered Resume Review System using Google Generative AI (Gemini) & Streamlit.

---

## 📖 Project Overview

Job hunting can be overwhelming — especially when rejection emails come without feedback.  
This inspired me to build *SmartATS Reviewer* — an intelligent application that helps job seekers analyze their resumes against job descriptions and provides actionable feedback.

By leveraging Google's Gemini Pro AI, this tool reviews resumes just like an Applicant Tracking System (ATS) would — and guides users on how to improve their profiles for better shortlisting chances.

---

## 1️⃣ Objectives

- Provide an automated resume review system for job seekers.
- Match resumes with job descriptions & highlight missing keywords.
- Generate skill improvement suggestions and profile summaries.
- Deliver a simple & user-friendly web interface for resume analysis.

---

## 2️⃣ Features

| Feature | Description |
|---------|-------------|
| Resume Upload | Upload your Resume in PDF format. |
| Job Description Input | Paste the target Job Description. |
| AI-Powered Analysis | Using Google Gemini AI for content analysis. |
| Resume Feedback | General profile feedback & summary generation. |
| Skills & Keywords Gap | Missing keywords detection. |
| Match Percentage | AI-based similarity score between Resume & JD. |

---

## 3️⃣ Technologies Used

- `Streamlit` — Web App Interface
- `Google Generative AI (Gemini Pro)` — Resume Analysis Engine
- `Python` — Backend Programming
- `PyPDF2` — PDF Text Extraction
- `python-dotenv` — Environment Variable Management

---

## 4️⃣ Challenges Faced

- Gemini API Integration & Prompt Engineering.
- Handling PDF parsing across various formats.
- Structuring AI Output for easy readability.
- Optimizing User Experience for clean & minimal UI.

---

## 5️⃣ Future Enhancements

- Support for multi-page detailed resumes.
- Interactive Resume Editing feature.
- Downloadable AI-Generated Resume Feedback Report.
- Smart Profile Suggestions based on specific Job Roles.
- Enhanced Error Handling for diverse file inputs.

---

## 6️⃣ Project Setup & Installation Steps

### Step 1: Clone the Repository
```bash
git clone <repo-link>
cd SmartATS-Reviewer
```

### Step 2: Create Virtual Environment

#### For Windows:
```bash
python -m venv venv
.env\Scriptsctivate
```

#### For MacOS/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

### Step 3: Install Required Dependencies
```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

### Step 4: Add Environment Variables

Create a `.env` file in your project directory and add your Google API Key from MakerSuite:

```
GOOGLE_API_KEY="your_makersuite_generated_key"
```

### Step 5: Run the Streamlit Application
```bash
streamlit run app.py
```

---

## 7️⃣ Sample Output Example

Example structure of AI response from Gemini:

```json
{
   "JD Match":"85%",
   "MissingKeywords":["Machine Learning", "SQL", "Data Pipeline"],
   "Profile Summary":"Strong candidate with good analytical skills. Improve technical skills in ML & data engineering."
}
```

---

## 8️⃣ Project Folder Structure

```
SmartATS-Reviewer/
│
├── app.py
├── requirements.txt
├── .env
├── venv/ (local virtual environment)
└── README.md
```

---

## 🙌 Conclusion

SmartATS Reviewer bridges the gap between job seekers and ATS systems by providing intelligent resume analysis & actionable feedback using cutting-edge AI.

This project aims to make the job application process smarter, more transparent, and user-friendly for everyone!

---

## 🔗 Connect With Me

Feel free to connect or collaborate if you like this project!
