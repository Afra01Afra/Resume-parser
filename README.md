Resume Parser App (Flask + NLP)
Objective
The Resume Parser App is designed to help recruiters quickly screen and analyze resumes. By uploading a PDF, the system extracts key details such as personal information, education, work experience, skills, projects, and certifications.

This tool leverages Flask, Natural Language Processing (NLP), and OpenAI's API to enhance the resume screening process, making hiring decisions faster and more efficient.

Features
✅ Upload resumes in PDF format
✅ Extracts structured data: Name, Contact, Experience, Skills, and more
✅ Uses NLP & AI for accurate text processing
✅ Displays extracted information in JSON format
✅ Recruiter-friendly UI with enhanced visuals & icons

Installation
Clone the repository

bash
Copy code
git clone https://github.com/your-repo/resume-parser.git
cd resume-parser
Install dependencies

bash
Copy code
pip install -r requirements.txt
Configure OpenAI API key

Add your OpenAI API key to the config.yaml file:
yaml
Copy code
openai_api_key: "your_openai_api_key_here"
Run the application

bash
Copy code
python app.py
Access the app
Open your browser and go to:
👉 http://localhost:8000

Usage
Upload a PDF resume.
The AI extracts key details.
Data is displayed in JSON format for easy review.
Recruiters can screen applicants faster and make data-driven hiring decisions.
Why Use This?
🔹 Automates resume screening
🔹 Reduces manual effort for recruiters
🔹 Enhances hiring accuracy with AI-powered insights

