 Intelligent-Resume-Analyser
 TRACE - Transparent Resume Alignment and Coverage Engine

TRACE is a Python-based Intelligent Resume Analyzer that compares a Job Description (JD) with a candidate's resume and evaluates how well the candidate matches the job requirements.

The system identifies relevant skills, determines requirement priority, checks candidate experience, calculates a weighted match score, and provides a suitability recommendation.


Project Objective

The main objective of TRACE is to reduce the manual effort involved in resume screening.

Recruiters often need to review a large number of resumes for a single job opening. TRACE provides a simple automated approach to analyze resumes against job requirements and generate a transparent requirement coverage report.



 Features

- Job Description analysis
- Resume analysis
- Skill extraction
- Skill variation detection
- Requirement priority classification
- Mandatory, Preferred, and Optional requirements
- Candidate experience analysis
- Matched requirement identification
- Missing requirement identification
- Evidence extraction from resume
- Weighted match score calculation
- Candidate suitability recommendation
- User-friendly Tkinter GUI
- Detailed requirement coverage report

---

 How It Works

The system follows these steps:

1. User enters the Job Description.
2. User enters the candidate's Resume.
3. The system normalizes the text.
4. Relevant skills are extracted.
5. Requirements are classified based on priority.
6. Resume skills are compared with job requirements.
7. Candidate experience is analyzed.
8. A weighted score is calculated.
9. Missing and matched requirements are displayed.
10. A final suitability recommendation is generated.



 Requirement Priority

TRACE assigns different weights to different types of requirements.

| Requirement Type | Weight |
|------------------|--------|
| Mandatory        | 5      |
| Preferred        | 3      |
| Optional         | 1      |

The weighted score is calculated based on the candidate's coverage of the identified requirements.



Recommendation Levels

| Score | Recommendation |
|------:|----------------|
| 90% and above | Highly Suitable |
| 75% - 89% | Suitable |
| 60% - 74% | Moderately Suitable |
| 40% - 59% | Low Suitability |
| Below 40% | Not Suitable |

A candidate with missing mandatory requirements may also receive a "Not Suitable" recommendation depending on the calculated score.

 Technologies Used

- Python
- Tkinter
- Object-Oriented Programming
- String Processing
- Lists
- Dictionaries
- Sets

No external Python packages or third-party APIs are required.
