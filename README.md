# 🎬 Netflix Data Analysis & Recommendation System Project

<center>
<img src="https://images.ctfassets.net/y2ske730sjqp/1aONibCke6niZhgPxuiilC/2c401b05a07288746ddf3bd3943fbc76/BrandAssets_Logos_01-Wordmark.jpg?w=940" width="350">
</center>

## 📌 Project Overview

This project focuses on analyzing Netflix's dataset to uncover insights about content distribution, trends, and patterns. Using data analytics techniques, visualizations, and machine learning approaches, the goal is to build a **Recommendation System** and present meaningful insights.

The project includes:

* Data loading & cleaning
* Exploratory data analysis (EDA)
* Visualizations
* Content-based recommendation system
* Insights and conclusions

---

## 📁 Files in This Repository

* **Netflix_Data_Analysis.ipynb** — Main analysis notebook
* **README.md** — Documentation (this file)
* **datasets/** — Netflix dataset (if included)
* **images/** — Visualizations & assets

---

## 🧹 Data Cleaning

Steps performed:

* Handling missing values
* Standardizing genres, ratings, and date fields
* Creating new features (e.g., content type mapping)

---

## 📊 Exploratory Data Analysis (EDA)

Some key questions explored:

* How has Netflix's content evolved over time?
* Which countries contribute the most content?
* What are the common genres?
* Movie vs TV Show distribution?

Visualizations include:

* Heatmaps
* Bar plots
* Word clouds
* Pie charts
* Country distribution maps

---

## 🤖 Recommendation System

A **Content-Based Filtering** approach was used where:

* Text features such as *description*, *genre*, *cast*, and *director* were vectorized
* Cosine similarity was used to recommend similar shows/movies

Example Output:

```
Input: "Money Heist"
Recommended:
1. Narcos
2. Pablo Escobar
3. Elite
4. Ozark
5. Queen of the South
```

---

## 📌 Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib & Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**

---

## 🚀 How to Run the Notebook

1. Clone the repository:

```bash
git clone <repo-link>
cd netflix-analysis
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Start Jupyter Notebook:

```bash
jupyter notebook
```

4. Open **Netflix_Data_Analysis.ipynb**

---

## 📈 Key Insights

* The number of releases peaked around 2018–2020.
* Movies dominate the platform compared to TV shows.
* US and India produce the most content.
* Drama and International Movies are the most common genres.

---

## 📝 Future Improvements

* Add a collaborative filtering model
* Deploy recommendation system using Streamlit
* Create a dashboard using Power BI/Tableau

---

## 💡 Author

Created by **MANI CHOKKARA** — Data Analyst & Tech Explorer.

If you like the project, feel free to ⭐ star the repo and contribute!

---

## 📬 Contact

For queries or collaboration:

* Email: [manichokkara2438@gmail.com](mailto:your-email@example.com)
* LinkedIn: https://www.linkedin.com/in/manichokkara/

---
