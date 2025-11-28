# Netflix-Movie-Data-Analysis-project

This project focuses on understanding patterns and trends in Netflix movie data, including genre popularity, IMDb score distribution, release trends, and viewer engagement metrics.
The analysis includes cleaning messy columns, handling genre lists, categorizing IMDb scores, and visualizing key patterns.

Data Cleaning & Preprocessing

Key cleaning steps performed:

Converted Release_Date to datetime format

Removed unnecessary fields like Poster_Url

Split comma-separated genres into lists

Applied .explode() to treat each genre as an individual row

Categorized IMDb score into buckets:

⭐ popular

👍 average

🙂 below_Average

👎 not_popualr

📊 Exploratory Data Analysis

The analysis includes:

🔸 1. Most Frequent Genres on Netflix

Using exploded Genres column, we identify dominant genres based on release frequency.

🔸 2. Distribution of IMDb Scores

Score categories reveal quality patterns across Netflix movies.

🔸 3. Popularity Trends

Detection of outliers and general popularity distribution.

🔸 4. Language-wise Comparison

Which original languages dominate Netflix releases.

🔸 5. Yearly Release Trends

Understanding Netflix’s movie release growth.

📈 Visualizations Used

Bar charts (Genre frequencies)

Countplots (IMDb score categories)

Histograms (Popularity, Vote Average)

Line plots (Yearly release trends)

Pie/donut charts (Language distribution)

🛠️ Tech Stack
Tool	Purpose
Python	Core analysis
Pandas	Data cleaning & transformation
NumPy	Numerical operations
Matplotlib / Seaborn	Data visualization
Jupyter Notebook	Interactive workflow

⭐ Key Insights

Some genres (like Drama, Comedy, Action) dominate Netflix releases.

IMDb score distribution is varied; only a small fraction falls under “Excellent.”

Popularity shows heavy right-tail → presence of high-popularity outliers.

English dominates as the most used original language.

Netflix’s movie catalog shows steady growth over the years.
