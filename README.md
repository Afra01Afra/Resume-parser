## **Resume Parser App (Flask + NLP + OpenAI)**  

### **Objective**  
The **Resume Parser App** helps recruiters quickly analyze resumes by extracting key details such as **personal information, education, work experience, skills, projects, and certifications**.  

Built with **Flask, NLP (Natural Language Processing), and OpenAI's API**, this tool **automates resume screening** and enhances hiring decisions.  

---

## **Features**  
✅ Upload resumes in **PDF format**  
✅ Extracts structured data: **Name, Contact, Experience, Skills, and more**  
✅ Uses **NLP & AI** for accurate text processing  
✅ Displays extracted information in **JSON format**  
✅ **Recruiter-friendly UI** with a modern design  

---

## **Installation**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/your-username/resume-parser.git
cd resume-parser
```  

### **2️⃣ Create a Virtual Environment (Optional but Recommended)**  
```bash
python -m venv venv
source venv/bin/activate   # For macOS/Linux
venv\Scripts\activate      # For Windows
```  

### **3️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```  

### **4️⃣ Configure OpenAI API Key**  
- **Create a file** named `config.yaml` in the root directory.  
- Add your OpenAI API key:  

  ```yaml
  openai_api_key: "your_openai_api_key_here"
  ```  

### **5️⃣ Run the Application**  
```bash
python app.py
```  

### **6️⃣ Open in Browser**  
Go to: **http://localhost:8000**  

---

## **Usage**  
1️⃣ **Upload a PDF resume**  
2️⃣ The **AI extracts** key details  
3️⃣ Data is displayed in **JSON format**  
4️⃣ Recruiters can **screen applicants faster** and make **data-driven decisions**  

---

## **Why Use This?**  
✅ **Automates resume screening**  
✅ **Saves recruiters time**  
✅ **Enhances hiring accuracy with AI**  

---

## **Tech Stack**  
- **Backend:** Flask (Python)  
- **NLP:** `nltk`, `spacy`, `pdfminer.six`, `docx2txt`  
- **AI:** OpenAI API  
- **Frontend:** HTML, Tailwind CSS  

---

## **Contributing**  
🔹 Feel free to **fork** this repo, create a branch, and submit a pull request!  

📧 **Need help?** Open an issue, and let’s build this together!

