# Football Beyond xG: Can Expected Goals Explain Football Outcomes?

## DSA210 Final Report

**Tuna Savaş**  
Sabancı University  
Spring 2025-2026

---

# 1. Motivation

As someone who plays and follows football closely, I have always been interested in the relationship between football and data science. Football is a sport where emotions, tactics, and randomness all exist together, which makes it interesting to analyze using statistical methods.

The main goal of this project is not to prove that xG perfectly predicts football success, but to analyze whether xG based statistics can help explain overperformance and underperformance in football. I also wanted to see whether machine learning models can use xG related features to predict team performance patterns.

---

# 2. Data Source

The dataset used in this project contains FIFA World Cup 2022 team statistics together with expected goals (xG) related metrics. The tournament included 32 national teams.

The dataset includes variables such as goals scored, goals conceded, expected goals scored, expected goals conceded, goal difference, wins, points, and xG difference values. The data was collected from publicly available football statistics sources and Kaggle datasets related to FIFA World Cup 2022 statistics and xG analysis.

The dataset was organized into CSV format and analyzed using Python libraries such as Pandas, NumPy, Matplotlib, and Scikit-learn inside Jupyter Notebook.

The project mainly focuses on understanding the relationship between expected goals statistics and actual football performance. For this reason, xG based variables were selected as the main features used throughout the analysis and machine learning stages.

---

# 3. Data Analysis

The project consists of two main parts: exploratory data analysis and machine learning analysis.

In the exploratory data analysis section, I first examined the structure of the dataset and analyzed the distributions of important variables such as goals scored, expected goals, and points. I also created visualizations including scatter plots, histograms, bar charts, and a correlation matrix in order to better understand the relationships between football performance metrics.

One important part of the analysis was comparing expected goals and actual goals scored. For this reason, I created an overperformance variable based on whether a team scored more goals than its expected goals value.

In the machine learning section, I used xG related statistics and football performance variables as features. The main features used in the models include expected goals scored, expected goals conceded, expected goal difference, points, wins, and goal difference.

The dataset was divided into training and test sets using train_test_split. I then compared three different machine learning classification models:

- Logistic Regression
- Decision Tree
- Random Forest

The performance of the models was evaluated using accuracy scores, confusion matrices, classification reports, and feature importance analysis. I also compared the models visually using accuracy comparison graphs.

---

# 4. Findings

The exploratory data analysis showed that there is a visible relationship between expected goals statistics and actual football performance. Teams with higher expected goals values generally scored more goals and collected more points throughout the tournament. However, the relationship was not perfect, which suggests that football outcomes are influenced by additional factors beyond xG statistics.

The visualizations also showed that some teams overperformed compared to their expected goals values, while others underperformed despite creating high quality chances. This supports the idea that finishing ability, defensive performance, and match context can strongly affect real match outcomes.

In the machine learning section, Logistic Regression achieved the highest accuracy score with approximately 0.7, while Decision Tree achieved around 0.6 and Random Forest achieved around 0.5. These results suggest that xG related features contain meaningful information for predicting football performance patterns.

Another important finding is that football remains difficult to predict perfectly even when advanced statistics are used. While xG based variables are useful indicators, they are not sufficient by themselves to fully explain why teams win, lose, overperform, or underperform during a tournament.

---

# 5. Limitations and Future Work

One important limitation of this project is the size of the dataset. Since the analysis only includes FIFA World Cup 2022 team statistics, the number of observations is relatively small for machine learning analysis. A larger dataset covering multiple leagues, tournaments, or seasons could produce more reliable and accurate results.

Another limitation is that football is naturally unpredictable. Factors such as player form, injuries, tactical decisions, goalkeeper performance, refereeing decisions, and luck can affect match outcomes but are not fully represented in the dataset.

The project also mainly focuses on team level statistics instead of detailed match or player level data. Future studies could use more advanced datasets containing shot locations, player actions, passing networks, or event based match data from sources such as StatsBomb.

In the future, I would also like to expand the analysis by including larger league datasets, including the Turkish Süper Lig and other major European leagues. Using season based league data instead of only tournament data could help create more accurate machine learning models and allow deeper analysis of long term football performance patterns. Additional visualization techniques and feature engineering methods could also improve the analysis and provide deeper insights into football analytics.

---

# 6. Conclusion

This project explored the relationship between expected goals statistics and actual football performance using FIFA World Cup 2022 data. Through exploratory data analysis, visualizations, and machine learning models, the project showed that xG based statistics are useful for understanding team performance patterns and overperformance behavior.

The analysis demonstrated that teams with stronger xG values generally performed better, but football outcomes still contain a significant level of unpredictability. The machine learning models achieved moderate success, which suggests that xG related features contain meaningful information but cannot fully explain football results on their own.

Overall, the project shows that data science methods can provide valuable insights into football analytics, while also highlighting the complexity and unpredictable nature of the sport.

---

# 7. AI Assistance Note

AI tools were used during parts of the project for assistance with code debugging, notebook organization, wording improvements, and report structuring. However, the dataset selection, data collection process, analysis decisions, final controls, interpretation of the results, and evaluation of the findings were completed and checked by me.
