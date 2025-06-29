# 📺 Netflix Movies & TV Shows EDA Project

This project performs an end-to-end **Exploratory Data Analysis (EDA)** on the Netflix Movies and TV Shows dataset using Python in Jupyter Notebook. The goal is to uncover hidden patterns, understand viewer preferences, clean the data, and provide recommendations for content strategy.


## 📂 Dataset Overview

- **Dataset**: `netflix_titles.csv` from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Records**: ~6,000+
- **Columns**: `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

## 🛠️ Tools & Libraries Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## ✨ Techniques Applied

- Data Cleaning & Preprocessing
- Missing Value Handling
- Duplicate Removal
- Outlier Detection using IQR
- Feature Engineering (month/year from `date_added`)
- Data Visualization with Seaborn and Matplotlib

---

## 🧪 Data Cleaning Summary

- Filled missing values (`director`, `cast`, `country`)
- Removed duplicates
- Standardized categorical values
- Extracted time-based features
- Detected and treated outliers using IQR method



## 📊 Key Visualizations

### 1. Movies vs TV Shows
![25](https://github.com/user-attachments/assets/7aafc029-d4fa-46c5-8feb-518a08074aa6)


### 2. Yearly Trend of Content Added

![8](https://github.com/user-attachments/assets/64fee5e2-ca2a-420e-b6ce-cb44f52bf0bd)

### 3. Top 10 Countries by Content

![9](https://github.com/user-attachments/assets/ab921964-a24a-4555-b408-7c86e96c57ae)

### 4. Ratings Distribution

![12](https://github.com/user-attachments/assets/54892eff-54b6-4771-a92f-85973e3c3034)

### 5. Top 10 Most Common Genres

![26](https://github.com/user-attachments/assets/dcec4d8e-656d-495d-b12b-a0b456b51c87)


### 6. Monthly Content Additions


![10](https://github.com/user-attachments/assets/64de03d9-1172-4cf8-a298-dc6b30dd24a8)

🔗 **[Click here to view all 21 graphs in the `images/` folder →](./images/)**

---

## 🧠 Key Insights

- **International Movies** dominate Netflix’s catalog, followed by **Dramas**
- Content peaked in **2018**, then slightly declined
- **United States** leads in total content share
- Most movies are ~90 minutes, shows mostly have **1 season**
- Viewers prefer **TV-MA** rated content and **international dramas**
- Peak in movie duration between **1960–1966** indicates experimentation
- Older TV shows (1960–1980) had **4+ seasons**, recent ones are shorter

---

## 🎯 Business Recommendations

- 📅 Improve content release in **February**
- 🌍 Focus more on **international content & short-form TV shows**
- 🎭 Invest more in **dramas** and globally relevant genres
- 🧩 Balance content from underrepresented countries
- ⏱️ Experiment with both long and short movie formats

---

## 📌 Skills Demonstrated

- Data Cleaning & Standardization
- Outlier Detection (IQR)
- EDA & Visualization
- Feature Engineering
- Business Insight Extraction
- Data Storytelling

---

## 📁 Project Structure

Netflix-EDA-Project/
│
├── Netflix_EDA.ipynb # Main notebook
├── netflix_titles.csv # Dataset
├── images/ # Folder with all 21 graphs
├── README.md # Project overview file

---

## ✅ Conclusion

This Netflix EDA project provides meaningful insights into viewer preferences, content trends, and strategies for optimizing Netflix’s global catalog. It showcases strong data cleaning, visualization, and storytelling capabilities — all essential for a data analyst role.


