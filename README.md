
<img width="1030" height="600" alt="image" src="https://github.com/user-attachments/assets/7e685b9c-d9b1-492b-921b-96b845f92ec3" />

SRINIVAS BHAIRI | Data Scientist Aspirant

[Connect me on LinkedIn](https://www.linkedin.com/in/srinivas-bhairi) 
---

# Netflix Data Exploration & Insights

This repository contains a complete **exploratory data analysis (EDA) project** on the Netflix dataset. The project moves from **basic data wrangling** (cleaning, handling null values, un-nesting columns) to **advanced business insights** (release strategies, country-level analysis, genre trends, licensing delays).

The goal of this project was to analyze Netflix’s content catalog (movies + TV shows) and extract **actionable insights** that can guide decisions on **content production, licensing, and release strategies**.

---

## 📌 Dataset

* Source: [Kaggle – Netflix Movies and TV Shows](https://www.kaggle.com/shivamb/netflix-shows)
* Records: \~8,800 titles (movies + TV shows)
* Features include: `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in` (genre), and `description`.

---

## 🔍 Analysis Workflow

1. **Data Preprocessing**

   * Un-nested multi-value columns (`cast`, `genre`, etc.).
   * Handled missing values with placeholders (`Unknown Director`, `Unknown Actor`).
   * Converted dates to datetime objects and extracted features (year, month, week).

2. **Exploratory Analysis**

   * Categorical distributions (content type, ratings, genres, countries).
   * Non-graphical (value counts) and graphical (count plots, bar charts, word clouds) exploration.
   * Comparison of **movies vs TV shows** across regions.

3. **Business-Oriented Insights**

   * **Best release time:**

     * Movies peak in **Jan, Jul, Sep–Oct, Dec**.
     * TV shows peak in **Jun–Jul & Dec**.
   * **Country distribution:** US dominates both categories; India is strong in movies but weak in TV; Japan & South Korea excel in TV shows.
   * **Top directors & actors:** Heavy catalog concentration on a few directors (e.g., Noam Murro, Alan Poul) and Indian movie stars (Anupam Kher, Shah Rukh Khan).
   * **Genre trends:** International movies, dramas, kids/family content, and action/adventure dominate.
   * **Licensing delays:** Most movies appear **6–12 months** after theatrical release, with a peak at \~547 days (1.5 years).

---

## 📊 Key Business Insights

* **Movies dominate Netflix’s catalog** (\~145k vs \~56k shows), showing a stronger focus on one-time consumption.
* **Content saturation**: Some titles/directors appear disproportionately, highlighting possible duplication or over-representation.
* **Mature-rated content (TV-MA, TV-14)** dominates; kids’ content is underrepresented.
* **Regional skew**: US leads, India is second in movies, Japan/Korea lead in TV shows.
* **Seasonality**: Best months for blockbuster movies are **Jan, Jul, Sep–Oct, Dec**; best for TV shows are **Jun–Jul, Dec**.
* **Release delay**: Average pay-1 window is \~1.5 years; strategy should target **<12 months** for competitiveness.

---

## 🛠️ Tech Stack

* **Language:** Python 🐍
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, WordCloud
* **Environment:** Jupyter Notebook / Google Colab

---

## 🚀 Recommendations

* Schedule **blockbuster movie releases** in **Jan, Jul, Sep–Oct, Dec**.
* Launch **major TV shows** in **Jun–Jul, Dec** for maximum engagement.
* Expand **kids/family catalog** to reduce churn in households.
* Invest in **regional content**: Indian TV, Japanese anime, Korean dramas.
* Reduce catalog duplication; diversify directors and actors.
* Negotiate shorter licensing delays (<12 months) for high-value titles.



Do you want me to also make this README **more eye-catching** with emojis, badges (Python, Jupyter, Pandas), and a banner-style project description at the top like many GitHub projects do?

