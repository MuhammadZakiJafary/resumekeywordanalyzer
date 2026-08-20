# Resume Keyword Analyzer

## 📌 Project Description

Resume Keyword Analyzer is a simple Python-based project that compares a resume with a job description. It checks the skills mentioned in both texts and shows the matched and missing skills.

The project also calculates a **keyword coverage percentage** to show how well the resume matches the job requirements.

---

## 🎯 Project Objective

The main goal of this project is to help candidates quickly understand whether their resume matches the skills required for a particular job.

Instead of checking the resume manually, the system automatically compares the skills and provides a simple report.

---

## 📥 Input

The project takes two inputs:

* Resume text
* Job description text

---

## 📤 Output

The system provides:

* Matched skills
* Missing skills
* Total required skills
* Keyword coverage percentage
* Final analysis report

---

## 🛠️ Technologies Used

* Python
* Google Colab
* Regular Expressions (Regex)
* Python Lists
* Python Sets

---

## ⚙️ How It Works

The project follows these steps:

1. Take the resume text.
2. Take the job description.
3. Convert the text into lowercase.
4. Clean the text.
5. Check the skills from the predefined skills list.
6. Compare the resume skills with the job skills.
7. Find matched skills.
8. Find missing skills.
9. Calculate keyword coverage.
10. Display the final report.

### Project Flow

```text
Resume + Job Description
          ↓
    Text Cleaning
          ↓
    Skill Extraction
          ↓
    Skill Comparison
          ↓
 ┌────────┴─────────┐
 ↓                  ↓
Matched Skills   Missing Skills
          ↓
   Coverage Percentage
          ↓
    Final Report
```

---

## 🧮 Keyword Coverage

The keyword coverage is calculated using:

```text
Keyword Coverage =
(Matched Skills / Total Required Skills) × 100
```

### Example

If the job description contains 5 required skills and the resume contains 3 of them:

```text
Matched Skills = 3
Total Required Skills = 5

Coverage = (3 / 5) × 100

Coverage = 60%
```

---

## 🧪 Example

### Resume

```text
I have knowledge of Python, SQL, Machine Learning,
Pandas and Scikit-learn.
```

### Job Description

```text
We need a candidate with Python, SQL, Machine Learning,
Pandas, TensorFlow and Docker.
```

### Result

```text
Matched Skills:
Python
SQL
Machine Learning
Pandas

Missing Skills:
TensorFlow
Docker

Keyword Coverage:
66.67%
```

---

## 📊 Sample Report

```text
========================================
RESUME KEYWORD ANALYSIS REPORT
========================================

Total Required Skills: 6
Matched Skills: 4
Missing Skills: 2

Keyword Coverage: 66.67%

MATCHED SKILLS
✓ Python
✓ SQL
✓ Machine Learning
✓ Pandas

MISSING SKILLS
✗ TensorFlow
✗ Docker
```

---

## 📁 Project Structure

```text
Resume-Keyword-Analyzer/
│
├── Resume_Keyword_Analyzer.ipynb
└── README.md
```

---

## ▶️ How to Run

This project is developed in **Google Colab**.

1. Open Google Colab.
2. Upload `Resume_Keyword_Analyzer.ipynb`.
3. Run the cells from top to bottom.
4. Enter the resume text.
5. Enter the job description.
6. Run the analysis.
7. View the matched skills, missing skills, and coverage percentage.

---

## 🧪 Testing

The project was tested using different resume and job description examples.

The following cases were tested:

* Resume with some matching skills
* Resume with all required skills
* Resume with no matching skills

The system successfully identified the matched and missing skills and calculated the keyword coverage for the test cases.

---

## ⚠️ Current Limitations

The current version has some limitations:

* It uses a predefined list of skills.
* It mainly uses keyword matching.
* It may not understand the meaning of similar words.
* It does not currently support direct PDF or DOCX upload.
* The accuracy depends on the skills included in the skills list.

---

## 🚀 Future Improvements

The project can be improved by adding:

* PDF resume upload
* DOCX resume support
* Automatic skill extraction
* Better NLP techniques
* Semantic similarity
* Resume improvement suggestions
* Charts and graphs
* ATS-style resume scoring
* Streamlit web interface

---

## 👨‍💻 Author

**Muhammad Zaki**

Software Engineering Graduate | AI/ML Enthusiast

---

## 📌 Conclusion

Resume Keyword Analyzer is a simple Python project that helps compare a resume with a job description.

It identifies the matched and missing skills and gives a keyword coverage percentage.

The project provides a basic foundation for building a more advanced AI-based resume analysis system in the future.
