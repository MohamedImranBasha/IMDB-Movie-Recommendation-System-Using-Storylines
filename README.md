# 🎬 IMDb 2024 Movie Recommendation System

This project builds a **movie recommendation system** using IMDb 2024 movie data.  
It analyzes movie storylines using **Natural Language Processing (NLP)** and recommends similar movies based on storyline similarity.

---

## 📌 Project Objective

To recommend movies with similar storylines by analyzing plot summaries using TF-IDF vectorization and Cosine Similarity.

---

## 🚀 Features

✔ Scrapes IMDb movie titles and storylines  
✔ Cleans and preprocesses text data  
✔ Converts text into numerical vectors using TF-IDF  
✔ Computes cosine similarity between movies  
✔ Recommends top 5 similar movies  
✔ Efficient recommendations using precomputed similarity matrix  

---

## 📂 Project Files

| File | Description |
|------|------------|
| `imdb_2024_movies.csv` | Raw scraped movie data |
| `cleaned_movies.csv` | Cleaned and processed dataset |
| `Data_Scraping_n_Processing.ipynb` | Scraping & preprocessing notebook |
| `Movie_Recommendation.py` | Recommendation engine |
| `tfidf_model.pkl` | Saved TF-IDF model |
| `tfidf_matrix.pkl` | TF-IDF vector matrix |
| `cosine_sim.pkl` | Cosine similarity matrix |

---

## 🧠 How It Works

### 1️⃣ Data Scraping
- Movie names and storylines were collected from IMDb.
- Stored in CSV format.

### 2️⃣ Data Cleaning & Preprocessing
- Removed punctuation and stopwords
- Cleaned and normalized text
- Saved as `cleaned_movies.csv`

### 3️⃣ Text Vectorization
- TF-IDF converts storylines into numerical vectors.
- Model saved for reuse.

### 4️⃣ Similarity Calculation
- Cosine similarity measures storyline similarity.
- Matrix stored for fast recommendations.

### 5️⃣ Recommendation Engine
- Loads similarity matrix
- Returns **Top 5 similar movies**

---

## 🧰 Technologies Used

### Language
- Python

### Libraries
- Pandas    
- NLTK
- Scikit-learn
- Selenium
- Streamlit (optional UI)

---

## ▶️ Installation

```bash
pip install pandas numpy nltk scikit-learn selenium streamlit


### Download NLTK resources:

import nltk
nltk.download('stopwords')
nltk.download('punkt')

### ▶️ Run Recommendation Script
python Movie_Recommendation.py
💡 Example

### Input Storyline:

A young hero discovers magical powers and battles dark forces.

### Output:

Movie 1 – Fantasy hero adventure

Movie 2 – Magical battle story

Movie 3 – Dark wizard conflict

Movie 4 – Mythical world journey

Movie 5 – Supernatural hero quest

### 📈 Business Applications

🎥 Personalized movie recommendations
📺 OTT content discovery
🍿 Entertainment suggestion engines
📊 Story similarity analysis

### 🔮 Future Improvements

Add Streamlit web interface

Include movie posters & ratings

Deploy online

Improve accuracy using deep learning

👨‍💻 Author

Imran Mohamed