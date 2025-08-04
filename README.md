# 🎬 Movie & Brand Analysis Project

This project analyzes IMDB Top 1000 movies and major movie production brands using **Python, Pandas, Matplotlib, Seaborn, and Machine Learning**.  
It generates visual insights, performs basic revenue predictions, and exports a **professional PDF report** for academic submission or industry use.

---

## 📌 Objectives

1. Perform **Exploratory Data Analysis (EDA)** on movie and brand datasets.
2. Visualize:
   - Top movie brands by lifetime gross
   - Top 10 IMDB-rated movies
   - Genre distribution
   - Director performance
   - Yearly movie trend
3. Perform **Linear Regression predictions** for:
   - Brand lifetime gross based on number of releases
   - Movie gross revenue based on IMDB votes
4. Generate a **complete PDF report** with all charts and analysis.

---

## 📊 Datasets

- **`bomojobrandindices.csv`**  
  Contains brand-wise box office performance:
Brand,Total,Releases,#1 Release,Lifetime Gross
Marvel Comics,15806336901,69,Avengers: Endgame,858373000
...


- **`imdb_top_1000.csv`**  
Contains IMDB top 1000 movies with fields like:
Series_Title,Released_Year,Genre,IMDB_Rating,No_of_Votes,Gross
The Shawshank Redemption,1994,Drama,9.3,2343110,28341469
...

---

## 🖥️ Features

- **Automatic Folder Structure**
- **6+ Data Visualizations**
- **Correlation Heatmap**
- **Revenue Prediction Models**
- **Professional PDF Report Generation**

---

## 📂 Project Structure

Movie_Brand_Analysis_Project/
├── data/
│ ├── bomojobrandindices.csv
│ └── imdb_top_1000.csv
├── src/
│ └── movie_analyst.py
├── output/
│ ├── charts/
│ └── Movie_Brand_Analysis_Report.pdf
├── README.md
└── requirements.txt

---

## ⚙️ Installation

1. Clone the repository or copy the folder.
2. Install dependencies:
   ```bash

   pip install -r requirements.txt
