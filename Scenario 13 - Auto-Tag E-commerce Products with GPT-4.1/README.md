# 🛍️ Data Scenario #13: Auto-Tag E-commerce Products with AI

Welcome to **Data Scenario #13**!  
In this project, we’ll build an system using GPT4.1 that **automatically categorizes e-commerce products** using **LangChain**, **OpenAI embeddings**, and **Python**. 🤖📦

---

## 📦 Scenario Overview

At **ShopSphere**, thousands of new products are uploaded every week.  
Manual tagging is slow and error-prone — it’s time to automate!

This project solves that problem using **semantic similarity** between product descriptions and predefined category labels.

### ✅ What You'll Build:
- Generate OpenAI embeddings for product descriptions  
- Compare them with category embeddings  
- Assign the most similar category using cosine similarity  
- Export the results to a CSV for review or upload

---

## 🛠️ Steps to Follow

### 1. Load Product Data
- Load a `products.csv` file containing product descriptions.

### 2. Generate Embeddings
- Use `LangChain` with `OpenAIEmbeddings` to vectorize:
  - Product descriptions  
  - Predefined category labels

### 3. Assign Categories
- Use `cosine_similarity` to compare vectors  
- Select the category with the highest similarity

### 4. Export Categorized Data
- Save predictions to a new CSV file  
- Ready for catalog management, analytics, or UI integration

---

## 🚀 Tech Stack

- [LangChain](https://www.langchain.com/)  
- [OpenAI Embeddings](https://platform.openai.com/docs/guides/embeddings)  
- [pandas](https://pandas.pydata.org/)  
- [scikit-learn](https://scikit-learn.org/)  
- [NumPy](https://numpy.org/)  

---

## 🎬 Watch the Tutorial

Follow the full video walkthrough on YouTube:  
📺 **[Watch Tutorial – coming soon](https://youtu.be/DDZbq5OLj6U)**  

---

## 💻 Get the Code & Notebook

Clone or download the full notebook here:  
👉 GitHub Repository: [https://github.com/ahmadvh/Data-Scenario](https://github.com/ahmadvh/Data-Scenario)

---

## 💡 Bonus Questions

- What other product metadata could be predicted using embeddings?
- Could this approach help improve your **search engine** or **recommendation system**?

---

## 📚 Part of the Data Scenario Series

This tutorial is part of the **Data Scenario** series — real-world business cases solved with Python, LLMs, and storytelling.

🔗 Full Playlist:  
[Data Scenarios on YouTube](https://www.youtube.com/playlist?list=PLgYONms4SxY3lkSrcN3Q9YoVCyLXuHkrT)

---

🙌 Don’t forget to **star** the repo and **subscribe** for more scenario-based AI builds!
