<h1 align="center">🎬 Netflix Movie Data Analysis Project </h1>

## 📌 Project Overview

This project focuses on analyzing a real-world movie dataset to extract meaningful insights using **Python**. The objective is to demonstrate end-to-end data analysis skills — from **data cleaning and preprocessing** to **exploratory data analysis (EDA)** and **visual storytelling**.

The analysis is designed to be easily understandable for both **technical and non-technical stakeholders**, with clear categorizations, structured workflow, and interpretable visualizations.

---

## 🗂️ Dataset Description

* The dataset contains approximately **9,000–10,000 movie records**.
* The dataset contains information about movies and TV shows available on Netflix, including details such as title, genre, release year, rating, language, poster URL, etc.

---

## 🧹 Data Cleaning & Preprocessing

The following steps were performed to prepare the dataset for analysis:

### 1. Data Type Conversion

* Converted `Release_Date` from **object** to **integer (year only)** for time-based analysis.
* Converted `Vote_Count` from **object** to **integer**.
* Converted `Vote_Average` from **object** to **float**.

### 2. Column Reduction

* Removed unnecessary columns that were not relevant for analysis to reduce noise and improve clarity.

### 3. Feature Engineering – Vote Categorization

To make insights more understandable for non-technical stakeholders, the `Vote_Average` column was categorized into four meaningful labels:

* **Not Popular**
* **Below Average**
* **Average**
* **Popular**

This transformation helped simplify numerical ratings into business-friendly categories.

### 4. Genre Processing

* Split multi-genre entries into lists.
* Exploded the dataset so that **each row represents one movie–one genre**.
* Cleaned whitespace and standardized genre values to ensure accurate analysis.

---

## 📊 Exploratory Data Analysis (EDA)

After preprocessing, data visualization techniques were applied to answer key analytical questions:

### Key Questions Answered

* **What is the most frequent genre in the dataset?**
* **Which genres receive the highest number of votes?**
* **Which year has the highest number of movie releases?**
* **Which movie has the highest popularity score?**

---

## 🔍 Key Insights

* **Drama** emerged as the most frequent genre in the dataset.
* Certain genres consistently received higher vote counts, indicating stronger audience engagement.
* **2020** recorded the highest number of movie releases.
* Movie popularity is fairly evenly distributed across categories such as *Popular*, *Average*, *Below Average*, and *Not Popular*.
* *Spider-Man: No Way Home* achieved the highest popularity score in the dataset.

---

## 🛠 Tools & Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas** – data manipulation & analysis
- **NumPy** – numerical operations
- **Matplotlib & Seaborn** – data visualization

---

## ▶️ How to Run the Project

1. Clone the repository
2. Install required libraries (`pandas`, `matplotlib`, `seaborn`)
3. Open the Jupyter Notebook and run cells sequentially

---

## ✅ Conclusion

This project demonstrates a structured and systematic approach to data analysis, covering:

* Data cleaning and preprocessing
* Feature engineering for better interpretability
* Exploratory data analysis using visualizations
* Insight generation aligned with real-world business and interview scenarios

---

## 📬 Contact

If you have feedback or suggestions, feel free to connect or raise an issue. This project was built for learning, practice, and continuous improvement.

