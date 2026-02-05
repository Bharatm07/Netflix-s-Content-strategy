# 🎬 Netflix Content Strategy Analysis

### In-Depth Exploratory Data Analysis (EDA)

> **A comprehensive exploratory data analysis of Netflix’s content library to uncover strategic insights into content production, acquisition, audience targeting, and global expansion.**

---

## 📌 Project Overview

Netflix has evolved from a DVD rental service into a global content powerhouse.
This project performs an **in-depth Exploratory Data Analysis (EDA)** on Netflix’s content catalog to understand:

* How Netflix’s **content strategy has evolved over time**
* The balance between **Movies vs. TV Shows**
* **Popular genres**, ratings, and durations
* **Geographical distribution** of content production
* Patterns in **content acquisition timing**
* Textual insights from **descriptions using NLP techniques**

The goal is not just visualization, but **business insight**—connecting data patterns to Netflix’s strategic decisions.

---

## 🎯 Objectives

* Analyze trends in **content addition over time**
* Identify **popular genres** and content formats
* Understand **audience maturity targeting** via ratings
* Study **content duration patterns**
* Explore **global content sourcing**
* Investigate **Netflix’s acquisition strategy** (new vs old content)
* Apply **basic NLP** to extract themes from content descriptions

---

## 🗂 Dataset

* **Source:** Netflix Movies and TV Shows dataset
* **Rows:** 7,787 titles
* **Features:** 12 original columns + engineered features

### Key Columns

* `type` (Movie / TV Show)
* `release_year`
* `date_added`
* `rating`
* `duration`
* `listed_in` (genres)
* `country`
* `description`

---

## 🧹 Data Cleaning & Feature Engineering

✔ Handled missing values strategically
✔ Converted dates to proper datetime format
✔ Engineered new features:

* `year_added`
* `month_added`
* `age_on_netflix` (Year Added − Release Year)

✔ Split multi-value columns (`genres`, `countries`) for granular analysis

---

## 📊 Key Analyses & Insights

### 1️⃣ Content Type Distribution

* ~70% of Netflix content consists of **Movies**
* TV Shows make up a smaller but steadily growing share

---

### 2️⃣ Content Growth Over Time

* Rapid increase in content additions after **2015**
* **Movies show sharper growth** compared to TV Shows
* Noticeable dip around **2020**, likely due to the COVID-19 pandemic

---

### 3️⃣ Genre Analysis

**Top Genres:**

* International Movies
* Dramas
* Comedies
* Action & Adventure

📌 *Insight:* Netflix strongly emphasizes **international and localized storytelling**, reinforcing its global strategy.

---

### 4️⃣ Content Duration Patterns

* Most movies fall between **80–120 minutes**
* Majority of TV Shows have **only 1 season**

📌 *Insight:* Netflix favors **limited series and pilots**, likely renewing only high-performing shows.

---

### 5️⃣ Geographic Distribution

**Top Content Producers:**

1. United States
2. India
3. United Kingdom
4. Japan
5. South Korea

📌 *Insight:* Netflix balances Hollywood dominance with aggressive investment in **regional markets**.

---

### 6️⃣ Audience Maturity & Ratings

* Majority of content is **TV-MA** and **TV-14**
* Clear rise in **mature content over time**

📌 *Insight:* Netflix primarily targets **adult audiences**, especially in original programming.

---

### 7️⃣ Content Age at Acquisition

* Large volume of content added **same year as release**
* Long tail of **older licensed content**

📌 *Insight:* Netflix combines **fresh originals** with **older catalog titles** to maximize library depth.

---

### 8️⃣ Multivariate Analysis

* Movie duration varies significantly by genre
* TV Shows span a **wider age range** than movies
* Older TV Shows are rarer than older movies

---

### 9️⃣ NLP & Text Analysis (Word Clouds)

* Frequent themes: *life, family, love*
* Common phrases (after stopword removal):

  * **High school**
  * Young man / young woman
  * Best friend
  * World war
  * Documentary series

📌 *Insight:* Netflix content heavily emphasizes **relationships, coming-of-age stories, and real-world narratives**.

---

### 🔟 Top Directors on Netflix

* Raúl Campos & Jan Suter
* Marcus Raboy
* Jay Karas
* Martin Scorsese
* Steven Spielberg

📌 *Insight:* A mix of **stand-up/comedy specialists** and **auteurs**, reflecting Netflix’s genre diversity.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas & NumPy** – Data manipulation
* **Matplotlib & Seaborn** – Data visualization
* **WordCloud & NLTK** – Text analysis
* **Jupyter Notebook**

---

## 📁 Project Structure

```
├── netflix_titles.csv
├── netflix_eda.ipynb
├── README.md
```

---

## 🚀 Key Takeaways for Recruiters

✔ Strong **EDA workflow**
✔ Thoughtful **data cleaning & feature engineering**
✔ Clear **business insights**, not just charts
✔ Exposure to **NLP & multivariate analysis**
✔ Clean, reproducible, and well-documented analysis

This project demonstrates the ability to **translate raw data into strategic insights**, a core skill for **Data Analyst / Data Scientist roles**.

---

## 📬 Contact

If you’d like to discuss this project or explore collaboration opportunities:

**[Your Name]**
📧 Email: *[your.email@example.com](mailto:your.email@example.com)*
🔗 LinkedIn: *your-linkedin-profile*
💻 GitHub: *your-github-username*

---

If you want, I can also:

* Rewrite this to target **FAANG / Netflix-style analytics roles**
* Add **resume bullet points**
* Create a **portfolio description**
* Optimize it for **ATS keywords**

Just say the word 🚀
