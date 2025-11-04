# 🏠 Airbnb Host Performance Analysis

## 📘 Project Overview
This project focuses on analyzing **Airbnb host performance in Paris**.  
The dataset was obtained from **Maven Analytics**, which provides real-world Airbnb data including information about hosts, listings, and reviews.

Since the dataset didn’t come with a predefined business problem, I decided to create my own **business scenario**:
> “Analyze hosts in Paris and identify key insights about their performance, experience, and listing characteristics.”

## 🎯 Objectives
- Understand and explore Airbnb host data.
- Clean and preprocess the dataset for accurate analysis.
- Discover trends, patterns, and key insights that explain host performance.
- Create an interactive Power BI dashboard for visualization and storytelling.

## 🧩 Dataset Description
The dataset contains information such as:
- Host details (name, ID, join date, total listings)
- Property information (room type, price, city)
- Reviews and ratings

**Data Source:** Maven Analytics (original) and public mirror on Kaggle.  
Kaggle dataset (used as dataset reference / download):  
https://www.kaggle.com/datasets/mysarahmadbhat/airbnb-listings-reviews

## 🧹 Data Preprocessing
All preprocessing was performed using **Python (Pandas, NumPy, and Datetime)**.  
Key steps included:

1. **Handling Missing Values**
2. **Removing Duplicates**
3. **Data Type Correction**
4. **Feature Engineering**
   - Extracted `host_join_year`
   - Calculated `host_experience_years`
5. **Fixing Invalid Data**
6. **Boolean Standardization**

## 📊 Exploratory Data Analysis (EDA)
EDA was done using **Python** and **Power BI**.

- **Univariate Analysis:** via `ydata_profiling`
- **Bivariate & Multivariate Analysis:** explored relationships between features

## 📈 Dashboard Creation (Power BI)
The dashboard visualizes:
- Host distribution
- Experience over time
- Price and review patterns
- Top-performing hosts
- KPIs and trends

## 💡 Key Insights
- Most active hosts are located in **Paris**.
- Experienced hosts generally receive **higher review scores**.
- **Entire home/apartment** listings tend to have higher average prices.
- Some hosts manage multiple listings, showing professional management behavior.

## 🧠 Tools & Technologies
Python | Pandas | NumPy | Power BI | ydata_profiling | Maven Analytics | Kaggle

## 🚀 Project Structure
Airbnb_Host_Performance_Analysis/
│
├── data/
├── notebooks/
├── visuals/
├── README.md
├── requirements.txt
└── powerbi_dashboard.pbix

## 🧾 Author
**Abdallah Ibrahim Mohamed Mostafa**  
🎓 Faculty of Computers and Data Science, Alexandria University  
💡 Data Science Enthusiast | Python | SQL | Power BI  
📧 abdallahebrahim785@gmail.com  
🌐 https://www.linkedin.com/in/abdallah-ibrahim-4556792a5?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app

## 🔗 Dashboard Access
You can view the interactive Power BI dashboard here:  
https://app.powerbi.com/view?r=eyJrIjoiYmFhMTg2NTMtYzhkMS00ZjNiLTgyZTctZDFmYjViOGYyZTk0IiwidCI6ImVhZjYyNGM4LWEwYzQtNDE5NS04N2QyLTQ0M2U1ZDc1MTZjZCIsImMiOjh9

## 📊 Dataset Access
The dataset used in this analysis can be downloaded from Kaggle (mirror of Airbnb listings & reviews):  
https://www.kaggle.com/datasets/mysarahmadbhat/airbnb-listings-reviews

---

### Notes
- The full raw dataset (Listings.csv) is large; in this repo we include a cleaned sample `data/listings_cleaned.csv` for reproducibility.  
- If you need access to the original raw files, download from the Kaggle link above or contact the author.
