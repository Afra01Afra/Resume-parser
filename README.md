# Resume Parser App (Flask + NLP)

### Objective

This project is a basic resume parser app built using Flask. The app allows users to upload their resumes in PDF format, and it extracts key details such as personal information, education history, work experience, skills, projects, and certifications. The extracted data is presented in JSON format, giving users an overview of their resume content.

To achieve this, the app utilizes Python along with libraries like Flask, pdfminer.six, docx2txt, nltk, and spacy for natural language processing. These tools help automate the process of extracting structured information from resumes, making the application useful for job seekers.

This app provides users with an easy way to check if their resumes are correctly formatted for parsing, making it suitable for general screening and analysis.

### Features

- Allows users to upload resumes in PDF format.
- Extracts structured data such as personal details, education, work experience, and skills.
- Displays extracted information in JSON format.
- Uses NLP techniques to process resume text.

### Installation

Follow these steps to set up the project:

1. Clone this repository to your local system.
2. Navigate to the project directory.
3. Install dependencies using:
   ```
   pip install -r requirements.txt
   ```
4. Add your OpenAI API key to the configuration file if required.
5. Start the application:
   ```
   python app.py
   ```
6. Open your browser and go to:
   ```
   http://localhost:8000
   ```

### Usage

- Upload a resume in PDF format.
- The app extracts relevant details and presents them in JSON format.
- Users can review the extracted data to check if their resumes are structured appropriately for screening purposes.

This project serves as a basic implementation of a resume parser, demonstrating the use of Flask and NLP for text extraction and structured analysis.

