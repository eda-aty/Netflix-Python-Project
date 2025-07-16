# 📽️ Netflix Data Cleaning Case Study

This project presents a data cleaning case study on a Netflix dataset using **Python** and **pandas**. It is designed to showcase essential data wrangling techniques and serve as a portfolio project for aspiring data analysts.

---

## 🚀 Project Motivation

Real-world datasets are often messy, incomplete, or inconsistent. This project simulates a typical data cleaning scenario where the goal is to transform raw data into a well-structured format ready for analysis or visualization.

---

## 📂 Dataset Overview

The dataset contains metadata about Netflix movies and TV shows, including:

- `show_id`: Unique identifier
- `type`: Movie or TV Show
- `title`, `director`, `cast`
- `country`, `date_added`, `release_year`
- `rating`, `duration`, `listed_in` (genres)
- `description`

Source: [Netflix Titles on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## 📊 Cleaning Tasks Performed

The following steps were taken to clean the dataset:

1. **Initial inspection**: Checked data types, structure, and summary
2. **Missing value treatment**:
   - Analyzed columns with NaN values
   - Replaced or removed rows based on context
3. **Date formatting**:
   - Converted `date_added` to datetime
4. **Standardization**:
   - Cleaned whitespace and text formatting
   - Unified inconsistent formats in columns
5. **Duplicates**:
   - Checked and removed any duplicate entries
6. **Final validation**:
   - Verified dataset shape and quality

---

## 🧰 Tools Used

- **Python**
- **pandas**
- **Google Colab**

---

## ✅ Results

The final dataset is clean, standardized, and ready for:

- Exploratory Data Analysis (EDA)
- Visualization dashboards (e.g., Tableau, Looker Studio)
- Machine learning pipelines (if applicable)

---

## 🚀 Next Steps

- Perform content trend analysis (by year, country, or genre)
- Build a dashboard to visualize streaming trends
- Integrate other streaming platforms for comparison

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `netflix_data_cleaning_case_study.ipynb` | Google Colab  containing full data cleaning steps |
| `README.md` | This documentation file |

---

## 👤 Author

**[Eda Aty]**  
*Junior  Data Analyst | *  
• [Portfolio](https://github.com/eda-aty/Portfolio-Guide))

---

## 📝 License

This project is open-source and available under the [Kaggle](LICENSE).

