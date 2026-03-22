# 🎬 Movie Recommendation System

A **Machine Learning and NLP-based Movie Recommendation System** that provides personalized movie suggestions based on your selected movie. Built using **Python**, **Streamlit**, and **NLP techniques**.

---

## 📝 Description

This project leverages **Natural Language Processing (NLP)** and **Machine Learning** to recommend movies similar to the one you like. The system analyzes movie metadata such as **title, genres, cast, and keywords**, processes them using NLP, and generates recommendations based on **similarity scores**.

---

## 🚀 Features

- Recommend movies based on **user-selected movie**  
- NLP-powered **text similarity** using TF-IDF and Cosine Similarity  
- Display **movie posters** for better user experience  
- Simple and **interactive UI** with Streamlit  
- Easily deployable on **Streamlit Cloud**  

---

## 🛠 Technology Stack

- **Frontend:** Streamlit  
- **Backend / ML:** Python, Pandas, NumPy, Scikit-learn  
- **NLP Techniques:** TF-IDF Vectorization, Cosine Similarity, Text Preprocessing  
- **Deployment:** Streamlit Cloud  

---

## 📊 Machine Learning & NLP Approach

1. **Data Preprocessing**
   - Load and clean movie metadata (title, genres, cast, keywords)
   - Handle missing values
   - Combine textual features into a single field for NLP

2. **Feature Extraction**
   - Apply **TF-IDF vectorization** on combined textual features
   - Convert text into numerical vectors representing movies

3. **Similarity Calculation**
   - Compute **cosine similarity** between movie vectors
   - Rank movies based on similarity to the selected movie

4. **Recommendation Logic**
   - Take user input (movie selection)
   - Fetch top-N similar movies using similarity scores
   - Display recommended movie titles and posters

5. **Pipeline Diagram**
   ```text
   Movie Metadata → Preprocessing → TF-IDF Vectorization → Cosine Similarity → Recommendations
---

## 🖼️ Screenshots

### 1️⃣ Home Page
![Home Page](https://github.com/anjalivarun13/Movie-Recommendation-System/blob/main/folder/page1.png)

### 2️⃣ Picture Section
![Picture Section](https://github.com/anjalivarun13/Movie-Recommendation-System/blob/main/folder/page2.png)

### 3️⃣ Recommendations (Scroll Down)
![Recommendations](https://github.com/anjalivarun13/Movie-Recommendation-System/blob/main/folder/page3.png)

### 4️⃣ More Like This / Genre
![More Like This](https://github.com/anjalivarun13/Movie-Recommendation-System/blob/main/folder/page4.png)

---

## 🎬 Demo

Check out the full demo of the **Movie Recommendation System**:

[![Watch Demo Video](https://cdn.jsdelivr.net/gh/streamable/thumbnail/oahzd9.png)](https://streamable.com/oahzd9)

---

## 🔹 Live Demo

Check out the deployed app: [Movie Recommendation System](https://movie-recommendation-system-anjalivarun.streamlit.app/)

---
