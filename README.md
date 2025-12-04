This project analyzes student feedback for different courses using Python, presenting insights through data preprocessing, visualization, and sentiment analysis.
The dataset contains questions, ratings, comments, and course information.
The goal is to understand satisfaction levels, identify issues, and generate actionable recommendations.

🔍 Features & Analysis Performed
✔️ 1. Dataset Overview
Displayed number of questions
Listed all dataset columns
Previewed the first 5 rows
Computed summary statistics of Average Score

✔️ 2. Visualizations (Dashboard)
Distribution of satisfaction scores (histogram + KDE)
Bar chart of average score per question
Average satisfaction by course
Sentiment pie chart (Positive / Neutral / Negative)
Boxplot comparing event types
Department-wise satisfaction bar chart
Word cloud of most common negative comments

✔️ 3. Derived Metrics
Extracted numerical rating from "Average/ Percentage".
Calculated Top 3 courses with highest satisfaction.
Generated sentiment labels using VADER:
Positive
Neutral
Negative

✔️ 4. Insights Generated
Most-liked departments (highest average score)
Most common complaints (from negative comment word cloud)
Correlation between question rating and event type (boxplot)
Top-performing courses based on student ratings

🛠️ Tech Stack
Python
Pandas
Seaborn / Matplotlib
NLTK (VADER Sentiment Analysis)
WordCloud
Ratings by department
