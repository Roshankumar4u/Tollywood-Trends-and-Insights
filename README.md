🎬 Tollywood Trends and Insights
📌 Project Overview

This project analyzes Telugu (Tollywood) movie data to uncover trends in:

🎥 Movie performance

💰 Budget vs Revenue

⭐ IMDb ratings

🎭 Genre-wise insights

📊 Profitability patterns

Using Python, Pandas, NumPy, Matplotlib, and Seaborn, this project provides meaningful insights through data analysis and visualization.

📂 Dataset

Dataset contains 405 Telugu movies

Features include:

Movie Title

Genre

Budget (Cr)

Director Success Rate

Lead Actor Success Rate

IMDb Rating

Trailer Views (Millions)

Box Office Revenue (Cr)

Released Year

🛠️ Technologies Used

Python 🐍

Pandas

NumPy

Matplotlib

Seaborn

🔧 Data Preprocessing

Removed duplicate records

Handled missing values

Dropped invalid IMDb entries

Converted data into structured format

df = pd.read_csv("telugu movie data with year")
df = df.dropna()
df = df[df["IMDb"] != 43]
📊 Key Insights
🎯 Statistical Analysis

Average Budget: ₹40.30 Cr

Median IMDb Rating: 6.6

Revenue Standard Deviation: ₹175.29 Cr

🏆 Top Performers

⭐ Highest IMDb Rated Movie: C/o Kancharapalem (9.5)

💰 Highest Revenue Movie: Baahubali 2: The Conclusion (₹1810 Cr)

📈 Profit Analysis

Created a new feature:

df["Profit"] = df["Box Office Revenue"] - df["Budget (Cr)"]

Top profitable movies:

Baahubali 2

Pushpa 2

Kalki 2898 AD

RRR

🎭 Genre Insights

Genres available:

Action

Comedy

Drama

Romance

Thriller

Highest revenue generating genre: Action

📉 Visualizations

The project includes various visualizations:

📊 Charts Used

Bar Plot → Top profitable movies

Pie Chart → Genre-wise revenue

Histogram → IMDb distribution

KDE Plot → Revenue before vs after 2015

Heatmap → Feature correlations

Scatter Plot → Trailer Views vs IMDb

Line Plot → Revenue trends over years

Count Plot → Movies per genre

Pair Plot → Feature relationships

🔍 Key Findings

🎬 Action movies dominate revenue

💡 Low-budget films can still be highly profitable

📈 Post-2015 movies show higher revenue trends

🎯 Trailer views have moderate correlation with success

⭐ IMDb rating doesn’t always guarantee box office success
