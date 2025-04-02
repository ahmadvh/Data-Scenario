# **Data Scenario #8: Personalized Book Recommendations with NMF**

Welcome to another Data Scenario! In this project, we’ll step into the shoes of a data scientist tasked with building a personalized recommendation engine for a growing online bookstore. 📚🎯

---

## **Scenario Overview**

You’ve been hired by **BookHive**, an online bookstore that wants to improve how users discover books they’ll love. Right now, BookHive relies on trending titles and editor picks — but that’s not enough. They want personalized suggestions based on actual user preferences.

**Your task:**  
Use **Non-negative Matrix Factorization (NMF)** to build a recommendation system that:
- Learns hidden patterns in user-book ratings.
- Predicts ratings for books a user hasn’t seen yet.
- Recommends books each user is likely to enjoy.

You'll be working with a real dataset containing user ratings for different books, and applying NMF to uncover the latent structure behind those ratings.

---

## **Steps to Follow**

### **1. Introduction to the Scenario**
- Understand BookHive’s challenge and the role of NMF in solving it.

### **2. Task 1 - Load and Inspect the Dataset**
- Load a dataset of user-book ratings.
- Explore its structure, unique users, and unique book counts.

### **3. Task 2 - Create the User-Item Matrix**
- Pivot the dataset to create a sparse matrix representing users vs. books.
- Handle missing values by filling them with zeros.

### **4. Task 3 - Apply NMF**
- Decompose the user-item matrix using NMF into two lower-dimensional matrices (`W` and `H`).
- Use a smart initialization (`nndsvd`) for better performance.

### **5. Task 4 - Predict Ratings**
- Multiply `W` and `H` to get a dense matrix of predicted ratings.

### **6. Task 5 - Make Recommendations**
- Build a function to recommend top-N books to any user based on the predicted scores.

### **7. Task 6 - Evaluate the System**
- Use **Root Mean Squared Error (RMSE)** to measure how close the predicted ratings are to known ones.

### **8. Task 7 - Tune Model Parameters**
- Test different values for `n_components` (latent features) to find the optimal model.
- Visualize the relationship between RMSE and number of components.

---

## **Watch the Tutorial**

Follow along with the scenario-based tutorial on YouTube:  
**[Video Tutorial](https://youtu.be/Xf3_WIcsvM0)**

---

## **Let’s Solve Together!**

This project is part of the **Data Scenario** series, where we solve real-world problems using Python, pandas, scikit-learn, and smart visual storytelling.

🚀 Learn by doing.  
🎓 Master real-world skills.  
📌 Subscribe for more: [YouTube Playlist](https://www.youtube.com/playlist?list=PLgYONms4SxY3lkSrcN3Q9YoVCyLXuHkrT)
