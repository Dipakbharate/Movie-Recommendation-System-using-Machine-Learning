# 🎬 Movie Recommendation Engine (Content-Based)

## 🚀 Overview
This project is a **Content-Based Movie Recommendation System** that suggests similar movies based on user preferences and movie metadata such as **genres, cast, and keywords**.

The system leverages **Natural Language Processing (NLP)** and **cosine similarity** to compute similarity scores and recommend the **top 5 relevant movies**.

---

## 💡 Problem Statement
With thousands of movies available, users often struggle to find relevant content.  
This system helps users discover movies similar to their interests using **data-driven recommendations**.

---

## 🧠 Key Features
- 🔍 Recommend top 5 similar movies instantly  
- 🎭 Uses metadata like genres, cast, and keywords  
- ⚡ Fast response time (< 2 seconds)  
- 🌐 Fetches real-time movie details using TMDB API  
- 🧹 Data preprocessing and feature engineering for better accuracy  

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn  
- **NLP Technique:** CountVectorizer (Bag of Words)  
- **Similarity Measure:** Cosine Similarity  
- **API Integration:** TMDB API  
- **Visualization (optional):** Matplotlib / Seaborn  

---

## ⚙️ How It Works

### 📥 Data Collection
- Movie dataset with metadata (genres, cast, keywords)

### 🧹 Data Preprocessing
- Handling missing values  
- Combining relevant features into a single text column  

### 🧠 Feature Extraction
- Applied **CountVectorizer** to convert text into vectors  

### 📊 Similarity Computation
- Used **cosine similarity** to calculate similarity scores  

### 🎯 Recommendation
- Sorted similarity scores  
- Returned **Top 5 similar movies**  

---

## 📌 Example

**Input:**  
Movie: Avengers


**Output:**  
Iron Man
Captain America: The First Avenger
Thor
Guardians of the Galaxy
Doctor Strange

---

## 📈 Performance
- ⚡ Recommendation response time: **< 2 seconds**
- 📊 Efficient similarity computation using vectorization
- ✅ Scalable for large movie datasets

---

## 🔗 API Integration
Integrated **TMDB API** to fetch:
- Movie posters  
- Ratings  
- Additional details  

---

## 📂 Project Structure

├── data/
├── notebooks/
├── app.py / main.py
├── similarity.pkl
├── movies.pkl
└── README.md


---

## 🖥️ How to Run Locally

---
# Clone the repository
git clone https://github.com/your-username/movie-recommendation-system.git

# Navigate to project folder
cd movie-recommendation-system

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
🎯 Future Improvements
✅ Add collaborative filtering
✅ Deploy as a web application
✅ Improve recommendations using deep learning
✅ Add user login & personalization
