
Capstone Project: Social Media, Student Habits, and Their Impact on Mental Health and Academic Performance

 Data Dictionary

| Variable Name              | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| `age`                     | Age of the student (numerical, in years)                                   |
| `gender`                  | Gender of the student (categorical: Male, Female, Other)                    |
| `education_level`         | Student level (categorical: Undergraduate or Graduate)                      |
| `country`                 | Country of the student (string)                                             |
| `avg_daily_usage`         | Average daily social media usage (in hours, float)                          |
| `most_used_platform`      | Most frequently used social media platform (e.g., Facebook, Twitter, etc.)  |
| `affects_academic_perf`   | Whether social media affects academic performance (Yes/No)                  |
| `sleep_hours`             | Average number of hours slept per night (float)                             |
| `addiction_score`         | Score reflecting level of social media addiction (scale 0–10)               |
| `exam_score`              | Academic performance score (numerical, 0–100 scale)                         |
| `mental_health_rating`    | Self-reported mental health score (scale 1–10)                              |
| `suicide_year`            | Year in which suicide-related data was recorded                             |
| `facebook_user`           | Boolean flag indicating if Facebook is used                                 |
| `twitter_user`            | Boolean flag indicating if Twitter is used                                  |
| `time_on_academics`       | Average daily hours spent on academic activities (float)                    |

---

 Data Summary

- **Total Records:** 3,000+
- **Demographics:**
  - Age range: 16–30 years
  - Gender: Male, Female, Other
  - Education Level: Undergraduate (approx. 75%), Graduate (25%)
  - Countries Represented: 20+ countries across North America, Europe, and Asia

- **Behavioral Statistics (approximate means):**
  - Average Daily Social Media Usage: **3.8 hours**
  - Average Sleep Hours per Night: **6.2 hours**
  - Average Addiction Score: **6.1/10**
  - Average Exam Score: **72.4/100**
  - Average Mental Health Rating: **5.6/10**

- **Correlations of Interest:**
  - Negative correlation between `addiction_score` and `exam_score`
  - Positive correlation between `sleep_hours` and `mental_health_rating`
  - Suicide data shows rising trends in years of high social media usage

---

 Data Sources

This project uses a unified dataset derived from the following Kaggle source:

- **Student Habits vs Academic Performance**  
  - Author: jayaantanaath  
  - Kaggle URL: [https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance)  
  - Accessed via: `kagglehub.dataset_download("jayaantanaath/student-habits-vs-academic-performance")`

> This dataset was cleaned and transformed using Python (pandas) in a Jupyter Notebook environment.*

---
 Tools & Libraries

- **Languages:** Python 3.x
- **Libraries:** `pandas`, `numpy`, `seaborn`, `matplotlib`, `plotly`, `scikit-learn`
- **IDE:** Visual Studio Code + Jupyter Notebook
- **Visualization:** Jupyter outputs, optional export to Tableau/Power BI

---

License & Attribution

Please check the Kaggle dataset page for license terms. This project is for educational and research purposes only.
