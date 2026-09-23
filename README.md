# 🚢 Titanic Survival Analysis — Task 2

### Data Science / Data Analysis with Python Internship — Main Crafts Technology

This repository contains my submission for **Task 2** of the 6-week virtual Data Science internship at **Main Crafts Technology**. The task involves analyzing the famous Titanic dataset to uncover patterns in passenger survival.

---

## 📁 Dataset

- **Name:** Titanic Dataset
- **Source:** [Kaggle — Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)
- **File used:** `titanic.csv`
- **Size:** 891 passengers, 12 attributes
- **Description:** The dataset includes passenger details such as age, sex, passenger class, fare, number of siblings/spouses and parents/children aboard, and whether they survived (`Survived`: 1 = survived, 0 = did not survive).

---

## 🎯 Objective

To perform a complete data analysis workflow — **load → clean → analyze → visualize → conclude** — and answer the following questions:

1. Who survived more: males or females?
2. Did passenger class affect survival chances?
3. What was the survival rate by age group?

---

## 🛠️ Tools & Libraries Used

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, and manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Core data visualization |
| `seaborn` | Statistical visualizations |

**Environment:** Google Colab

---

## 📅 Day-wise Progress

| Day | Stage | Notebook |
|---|---|---|
| Day 1 | Load dataset & first look | [`Day1_Data_Loading_Task2.ipynb`](notebooks/Day1_Data_Loading_Task2.ipynb) |
| Day 2 | Explore & clean data | [`Day2_Data_Cleaning_Task2.ipynb`](notebooks/Day2_Data_Cleaning_Task2.ipynb) |
| Day 3 | Answer analysis questions | [`Day3_Analysis_Task2.ipynb`](notebooks/Day3_Analysis_Task2.ipynb) |
| Day 4 | Visualizations | [`Day4_Visualizations_Task2.ipynb`](notebooks/Day4_Visualizations_Task2.ipynb) |
| Day 5 | Final report & conclusion | [`Day5_Final_Report_and_Conclusion_Task2.ipynb`](notebooks/Day5_Final_Report_and_Conclusion_Task2.ipynb) |

The final, complete notebook combining all stages is available at [`Titanic_Survival_Analysis_Task2.ipynb`](Titanic_Survival_Analysis_Task2.ipynb).

---

## 🔍 Key Findings

- 🧹 Real-world messy data: `Age` had **177 missing values** (filled with median), `Cabin` had **687 missing values** (dropped — too sparse to be useful), and `Embarked` had 2 missing values (filled with mode).
- 👩 **Gender was the strongest predictor of survival** — female passengers survived at **~74%**, compared to **~19%** for male passengers, reflecting the "women and children first" evacuation protocol.
- 🎟️ **Passenger class strongly affected survival chances** — 1st class passengers survived at **~63%**, 2nd class at **~47%**, and 3rd class at only **~24%**.
- 👶 **Age group also mattered** — children had a comparatively higher survival rate than adults, though the effect was smaller than gender or class.

---

## 📈 Visualizations

| Chart | Insight |
|---|---|
| Bar Chart: Survival by Gender | Females survived at a much higher rate than males |
| Bar Chart: Survival by Class | Survival rate drops steadily from 1st to 3rd class |
| Histogram of Passenger Ages | Most passengers were aged 20–40, peak near the mean (~29) |

Chart images are available in the [`visuals/`](visuals/) folder.

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/titanic-survival-analysis.git
   ```
2. Download `train.csv` from the [Kaggle Titanic competition page](https://www.kaggle.com/c/titanic/data).
3. Open `Titanic_Survival_Analysis_Task2.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
4. Run the first code cell — it will prompt you to upload `train.csv`, then load it directly into the analysis.

---

## 📌 Conclusion

This task extended the data science workflow from Task 1 to a messier, real-world dataset. The key takeaway: **gender and passenger class were the biggest drivers of survival**, echoing real historical evacuation priorities — a strong reminder that context and domain knowledge matter as much as the numbers themselves.

---

## 🔗 Connect

This project was completed as part of the **6-week virtual internship at Main Crafts Technology**.

#DataScience #Python #Pandas #Seaborn #TechInternship #Maincrafts
