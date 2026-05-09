Book Recommendation Engine using KNN
🚀 Overview

This project is a machine learning-based book recommendation system built using the K-Nearest Neighbors (KNN) algorithm. It suggests books similar to a given book based on user rating patterns.

📊 Dataset

We use the Book-Crossings dataset:

📚 1.1M ratings
📖 270K books
👥 90K users
Data filtering:
Users with ≥ 200 ratings
Books with ≥ 100 ratings

This ensures meaningful recommendations.

🧠 Approach
🔹 Algorithm:
K-Nearest Neighbors (KNN)
Cosine similarity metric
🔹 Steps:
Load dataset
Clean and filter data
Create user–book matrix
Train KNN model
Compute nearest neighbors
Return top 5 similar books
⚙️ Tech Stack
Python 🐍
Pandas
NumPy
Scikit-learn
SciPy
📌 Core Function
get_recommends("Book Title")
📤 Output format:
[
  "Book Title",
  [
    ["Similar Book 1", 0.78],
    ["Similar Book 2", 0.75],
    ["Similar Book 3", 0.72],
    ["Similar Book 4", 0.70],
    ["Similar Book 5", 0.68]
  ]
]
📈 Model Details
Algorithm: KNN (Brute Force)
Metric: Cosine Distance
Data Structure: Sparse Matrix (CSR)
🎯 Objective

To recommend books based on reading similarity patterns, not just popularity.

📁 Project Structure (GitHub Ready)
book-recommender-knn/
│
├── book_recommender.ipynb   # Main notebook
├── README.md                # Project documentation
└── requirements.txt        # Dependencies (optional)
📦 requirements.txt (optional but pro)
numpy
pandas
scikit-learn
scipy
matplotlib
🏁 How to Run
Clone repo
git clone https://github.com/your-username/book-recommender-knn.git
Open notebook
jupyter notebook
Run all cells
⭐ Future Improvements
Add content-based filtering
Hybrid recommendation system
Web app using Flask / Streamlit
👨‍💻 Author

Built as part of Machine Learning certification project.
