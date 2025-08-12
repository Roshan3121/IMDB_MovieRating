# 🎬 Movie Ratings Analysis

An exploratory data analysis (EDA) project on IMDb movie data (2006–2016) using Python, Pandas, and Seaborn.  
The goal is to uncover trends in movie ratings, identify top genres and directors, and explore relationships between ratings, revenue, and other features.

---

## 📊 Dataset
- **Source:** IMDb (2006–2016 dataset)
- **File:** `IMDB-Movie-Data.csv`
- **Columns include:**
  - `Title` — Movie name
  - `Genre` — Genres (comma-separated)
  - `Director` — Director’s name
  - `Actors` — Main cast
  - `Year` — Release year
  - `Runtime (Minutes)`
  - `Rating` — IMDb rating
  - `Votes` — Number of votes
  - `Revenue (Millions)`
  - `Metascore`

---

## 🔍 Analysis Steps
1. **Data Cleaning**
   - Removed duplicates
   - Handled missing values in revenue and metascore
   - Extracted primary genre from multi-genre entries

2. **Exploratory Data Analysis**
   - Top genres by average rating
   - Top directors with ≥3 movies
   - Trends in ratings over time
   - Correlation between revenue and ratings

3. **Visualizations**
   - Bar charts for genres and directors
   - Line chart for ratings over the years
   - Scatter plot for ratings vs revenue

---

## 📈 Key Insights
- Drama and Biography genres tend to have the highest ratings.
- Financial success does **not** strongly correlate with critical ratings.
- Certain directors maintain consistently high ratings over multiple movies.
- Ratings remained fairly stable from 2006 to 2016.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Project Structure
