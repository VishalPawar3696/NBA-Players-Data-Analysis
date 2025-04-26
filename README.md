🏀 #NBA Player Analysis and Dashboard Project
📂 #Project Overview
This project focuses on analyzing NBA players' performance across different seasons.
We perform data cleaning, exploratory data analysis (EDA) using Pandas and visualization libraries,
then create an interactive dashboard in Power BI for player and team comparisons.

🛠️ Tools & Technologies Used
Python (Pandas, Matplotlib, Seaborn)

MySQL (Database to store cleaned data)

SQLAlchemy (Python library to connect with MySQL)

Power BI (For creating dynamic dashboards)

GitHub (Version control and project showcasing)

📊 Project Workflow

1.Data Collection & Processing

Downloaded the all_seasons.csv dataset.

Loaded into Pandas DataFrame.

Handled missing values (e.g., "Undrafted" → NULL).

Normalized fields like season kept as text (1996-97, etc.).

2.Exploratory Data Analysis (EDA)

Analyzed players' points, assists, rebounds trends.

Visualized data using Matplotlib and Seaborn.

Distribution of stats by player position.

Season-wise performance trends.

3.Database Creation

Cleaned dataset uploaded into MySQL database using SQLAlchemy.

Created tables and wrote simple SQL queries for insights.

4.Power BI Dashboard

Connected Power BI to MySQL database.

Built interactive KPIs:

Total Points

Total Assists

Total Rebounds

Created Player Comparison Section (using slicers for selecting players).

5.Added multiple visuals:

Bar charts

Line charts

Scatter plots

Slicers for dynamic filtering

Summary Section showing top players and teams.


🖼️ Screenshots
1. Data Cleaning & EDA (Python)

2. SQL Database Table

3. Power BI Dashboard


🚀 How to Run the Project
1.Clone the repository:
git clone https://github.com/yourusername/nba-player-analysis.git

2.Install required libraries:
pip install pandas matplotlib seaborn sqlalchemy pymysql

3.Run the Python files to clean the dataset.

4.Upload cleaned data into your MySQL database.

5.Open Power BI → Connect to MySQL → Load data → Dashboard ready!
