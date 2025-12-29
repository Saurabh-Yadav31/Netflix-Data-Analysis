# Netflix Data Analysis 📊

This project performs Exploratory Data Analysis (EDA) on a Netflix movies dataset using Python and Jupyter Notebook.  
The goal is to understand trends in genres, popularity, ratings, and yearly releases.

---

## 📁 Dataset Overview

- **9827 rows** and **9 columns**
- No missing values or duplicated records
- Important columns analyzed:
  - `title`
  - `genre`
  - `release_date`
  - `popularity`
  - `vote_average`

Some columns such as `Overview`, `Original_language`, and `Poster_URL` were dropped because they were not useful for analysis.

Release dates were converted to **year format**, and the `genre` column was cleaned by splitting comma-separated values and removing extra spaces.

---

## 🔍 Main Analysis Performed

### ✔️ Data Cleaning
- Converted date fields
- Removed unnecessary columns
- Handled outliers
- Split and exploded genre lists
- Categorized `vote_average` into rating groups

### ✔️ Visual Analysis
Visualized insights such as:

- Most frequent movie genres
- Trends in popularity
- Rating distribution
- Popularity highs and lows
- Movie counts by year

---

## ⭐ Key Insights

- **Drama** is the most common genre (appears ~14% of the time)
- Around **25% of movies received high vote averages**
- **Spider-Man: No Way Home** has the **highest popularity**
- **2020** is the year with the most movies released
- Popular genres like **Action** and **Adventure** dominate top-rated movies

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ▶️ How to Run

1. Clone the repository  
2. Install dependencies (optional later using `requirements.txt`)
3. Open the notebook:


---

## 📓 Notebook

- **Netflix_DA.ipynb** — contains full cleaning, analysis, and visualizations.

---

## 🚀 Future Improvements

- Add dashboards using Plotly
- Include additional Netflix datasets
- Build predictive models on popularity or ratings

---

### 👤 Author
Saurabh Yadav 

