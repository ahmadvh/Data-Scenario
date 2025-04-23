# **Data Scenario #12: Resume Parser with LangChain** 📄🤖

Welcome to this Data Scenario! In this project, you’ll build an AI-powered **Resume Parser** using **LangChain** and **OpenAI**, transforming PDF resumes into structured JSON or pandas DataFrames for easy analysis. 🧠📊

---

## **Scenario Overview**

Let’s say you're building a tool to help recruiters or HR professionals quickly review and extract information from resumes. Instead of manually reading each one, your system will:

- Parse resumes in PDF format  
- Extract key information like name, skills, education, and work experience  
- Structure the results as JSON or in a pandas DataFrame for downstream tasks

**Your task:**  
Use **Python**, **LangChain**, and **OpenAI** to extract structured data from unstructured resume text.

---

## **Steps to Follow**

### **1. Extract Text from PDF**
- Load a PDF using `PyPDF2` and extract raw text.

### **2. Use LangChain + OpenAI to Parse Info**
- Create a prompt to guide the LLM in extracting structured info like:
  - Full Name  
  - Email  
  - Phone Number  
  - Skills  
  - Education (degree, institution, year)  
  - Work Experience (role, company, years)

### **3. Parse and Display Output**
- Convert the AI's response to JSON  
- Display it cleanly with `pandas` for analysis or downstream applications

---

## **🚀 Technologies Used**

- `LangChain`  
- `OpenAI GPT-4.1-mini`  
- `PyPDF2`  
- `pandas`  
- `dotenv` for API key management

---

## **🎬 Watch the Tutorial**

Follow along with the scenario-based tutorial on YouTube:  
📺 **[Video Tutorial](https://youtu.be/1RLJLhPGFoE)**

---

## **💻 Get the Code & Notebook**

Follow along with the full notebook and all the project files here:  
👉 GitHub Repository: https://github.com/ahmadvh/Data-Scenario

📌 Don’t forget to like, subscribe, and check out the full Data Scenarios playlist:  
https://www.youtube.com/playlist?list=PLgYONms4SxY3lkSrcN3Q9YoVCyLXuHkrT

---

## **Let’s Solve Together!**

This project is part of the **Data Scenario** series, where we solve real-world problems using Python, data tools, and storytelling.

🚀 Learn by doing.  
🎓 Master real-world skills.  
📌 Subscribe for more: [YouTube Playlist](https://www.youtube.com/playlist?list=PLgYONms4SxY3lkSrcN3Q9YoVCyLXuHkrT)
