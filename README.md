# 🎬 Netflix Data Analysis & Recommendation System  

![Netflix Banner](https://github.com/Sugam-100/Netflix-Data-Analysis-and-Recommendation-System/blob/main/Netflix%20Dashboard%20Snapshort.png)  


---

## 📌 Overview  
This project analyzes the **Netflix dataset** and builds a **Movie Recommendation System**.  
It provides **insights into movies & TV shows** on Netflix and recommends content based on similarity.  

The workflow includes:  
- Data Collection (from CSV / MySQL database)  
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA) with visualizations  
- Dashboard creation (Power BI / Python)  
- Content-Based Movie Recommendation System  

---

## 📂 Dataset  
- Source: [Netflix Dataset](https://www.kaggle.com/shivamb/netflix-shows)  
- Contains details like:  
  - Title  
  - Type (Movie/TV Show)  
  - Director  
  - Cast  
  - Country  
  - Release Year  
  - Rating  
  - Duration  
  - Description  

---

## ✨ Features  
- Cleaned and structured Netflix dataset  
- Interactive Dashboard with key insights  
- Visualizations for trends in Netflix content  
- Movie Recommendation System (`recommend("3 Idiots")` → suggests similar movies)  

---

## 📊 Dashboard Insights  

Here are some key insights from the dashboard:  
- 📈 Number of movies vs. TV shows on Netflix  
- 🌍 Content distribution across countries  
- 📅 Year-wise trend of content release  
- ⭐ Top genres and ratings  
- 🎭 Most frequent actors & directors  

📌 **Dashboard Screenshot:**  
![Dashboard Screenshot](dashboard/dashboard.png)  
*(Replace with your exported dashboard image in the `dashboard/` folder)*  

---

## 🛠 Tech Stack  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
- **MySQL** (Data storage & integration)  
- **Power BI / Matplotlib** (Dashboard & visualization)  
- **Jupyter Notebook** (Data Analysis workflow)  

---

## 🔎 Exploratory Data Analysis (EDA)  
Some questions answered in EDA:  
- Which country produces the most Netflix content?  
- What is the distribution of Movies vs TV Shows?  
- Which directors and actors are most featured?  
- How has Netflix content grown over the years?  
- Which genres dominate Netflix?  

---

## 🎯 Recommendation System  
- Approach: **Content-Based Filtering** (using TF-IDF Vectorization + Cosine Similarity)  
- Example:  
```python
recommend("3 Idiots")
