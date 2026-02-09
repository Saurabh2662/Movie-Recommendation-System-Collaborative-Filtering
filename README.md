# 🎬 Movie Recommender System

A simple **Movie Recommendation System** built using **Collaborative Filtering** and **Content-Based Filtering** techniques.  
This project is inspired by real-world recommendation systems used by platforms like Netflix and Amazon.

---

## 📌 Overview

The goal of this project is to explore how recommendation systems work by implementing and comparing:
- **Collaborative Filtering (CF)**
- **Content-Based Filtering**

Each approach has its own strengths and limitations, and this project demonstrates how they can be used together.

---

## 🧠 Recommendation Techniques

### 🔹 Collaborative Filtering
Collaborative filtering recommends movies based on **user–item interactions**.

This project includes:
- **Model-based CF** using **Singular Value Decomposition (SVD)**
- **Memory-based CF** using:
  - User-User similarity
  - Item-Item similarity

⚠️ **Limitation:**  
Collaborative filtering suffers from the **cold-start problem** when new users or movies are added.

---

### 🔹 Content-Based Filtering
Content-based filtering recommends movies based on **similarity between items**.

Key idea:
> If a user likes a movie, they are likely to enjoy movies with similar content.

✅ Works well for new users  
✅ Does not rely on other users’ data  

---

## 📂 Project Files

- **`Collaborative-filtering.py`**  
  Implements model-based (SVD) and memory-based collaborative filtering.

- **`Content-based.py`**  
  Generates recommendations using item similarity.

- **`app.py`**  
  Flask application that deploys the **content-based recommendation model**.

---

## ▶️ How to Run

```bash
python app.py

