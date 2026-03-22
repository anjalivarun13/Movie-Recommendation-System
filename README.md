# 🎬 Movie Recommendation System - Using NLP
## 🔍Project Overview

A **Machine Learning and NLP-based Movie Recommendation System** that provides personalized movie suggestions based on your selected movie. Built using **Python**, **Streamlit**, and **NLP techniques**.

---

## 📝 Description

The system leverages **Natural Language Processing (NLP)** and **Machine Learning** to generate recommendations. It analyzes movie metadata such as:

- **Title**  
- **Genres**  
- **Votings**  
- **Keywords / Plot**  

Textual features are preprocessed, vectorized using **TF-IDF**, and similarity is calculated using **Cosine Similarity** to recommend relevant movies.

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

## 🖼️ Movie Recommendation System Screenshots

### 1️⃣ Home Page
![Home Page](https://github.com/anjalivarun13/Movie-Recommendation-System/blob/main/Screenshot/page1.png)

### 2️⃣ Picture Section
![Picture Section](https://github.com/anjalivarun13/Movie-Recommendation-System/blob/main/Screenshot/page2.png)

### 3️⃣ Recommendations (Scroll Down)
![Recommendations](https://github.com/anjalivarun13/Movie-Recommendation-System/blob/main/Screenshot/page3.png)

### 4️⃣ More Like This / Genre (Scroll Down)
![More Like This](https://github.com/anjalivarun13/Movie-Recommendation-System/blob/main/Screenshot/page4.png)

---

## 🎬 Video Demo

Check out the full demo of the **Movie Recommendation System**:

[![Watch Demo Video](https://cdn.jsdelivr.net/gh/streamable/thumbnail/oahzd9.png)](https://streamable.com/oahzd9)

---

## 🔹 Live web Demo

Check out the deployed app: [Movie Recommendation System](https://movie-recommendation-system-anjalivarun.streamlit.app/)

---

## ⚙️ Installation

### Clone the repository
```bash
git clone https://github.com/your-username/movie-recommendation-system.git
```

### Create virtual environment
```bash
python3.11 -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows
```
### Install dependencies
```bash
pip install -r requirements.txt
```

### Run the Streamlit app
```bash
streamlit run app.py
```
---
# 🔮 Future Improvements
- Upgrade NLP model to **BERT / Sentence Transformers** for better semantic understanding
- Implement **hybrid recommendation (content + collaborative filtering)**
- Add user **profiles** for personalized recommendations
- Enable **real-time API integration** for dynamic data

---

# 🙏 Credits & Acknowledgements
- **Dataset:** Kaggle MovieLens Dataset
- **Libraries:** Pandas, NumPy, Scikit-learn, Streamlit
- Inspired by existing movie recommendation tutorials and ML/NLP techniques

---
# Author

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/Machine_Learning-✅-brightgreen)](https://en.wikipedia.org/wiki/Machine_learning)
[![NLP](https://img.shields.io/badge/NLP-✅-red)](https://en.wikipedia.org/wiki/Natural_language_processing)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

**Author:** Anjali Varun  
**GitHub:** [anjalivarun13](https://github.com/anjalivarun13)  
**LinkedIn:** [anjalivarun](https://www.linkedin.com/in/anjali-varun/)
