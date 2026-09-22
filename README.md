# 🎬 Netflix Content Strategy & Catalog Analysis

An end-to-end exploratory data analysis (EDA) project evaluating over 15 years of Netflix catalog data. This project utilizes an integrated SQL and Python pipeline to uncover insights regarding content distribution, global geographic supply, maturity ratings, and strategic white spaces.

---

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Database:** SQLite (In-memory execution)
* **Data Manipulation:** Pandas
* **Data Visualization:** Matplotlib
* **Environment:** Jupyter Notebook

---

## 📊 Project Scope & Analyses
1. **Content Ratio:** Evaluated the proportion of Movies vs. TV Shows in the historical library.
2. **Geographic Distribution:** Identified top content-producing countries and analyzed international market saturation.
3. **Temporal Evolution:** Tracked historical production trends from 2010 to 2021 using SQL `CASE WHEN` aggregations.
4. **Audience Maturity Ratings:** Analyzed target demographic breakdowns across adult and family programming.
5. **Runtime Distribution:** Cleaned runtime string data in SQL (`REPLACE`, `CAST`) to analyze feature film duration spreads.
6. **Genre Extraction:** Used SQL string parsing (`INSTR`, `SUBSTR`) to parse and analyze primary content genres.

---

## 💡 Key Business Takeaways
* **Catalog Mix:** Feature films comprise roughly 70% of total titles, though episodic TV show volume scaled significantly post-2015 to drive long-term retention.
* **Geographic Imbalance:** Production is heavily anchored by the U.S. and India, highlighting a massive expansion opportunity in localized European and Latin American markets.
* **Demographic Saturation:** Over 60% of programming targets mature audiences (TV-MA / TV-14), leaving family-friendly tiers underindexed compared to competitors like Disney+.

---

## 🚀 How to Run the Code
1. Clone this repository:
   ```bash
   git clone [https://github.com/your-username/netflix-content-strategy-analysis.git](https://github.com/your-username/netflix-content-strategy-analysis.git)
