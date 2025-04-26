🏀 #NBA Player Analysis and Dashboard Project

📂 #Project Overview
![Screenshot (58)](https://github.com/user-attachments/assets/9328d6cf-50b1-4a90-ae66-f0c783dd348c)

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
1. Data cleaning & EDA (Python)
![Screenshot (53)](https://github.com/user-attachments/assets/ceea5911-3792-434c-94a5-3d7d7e4537c6)
![Screenshot (51)](https://github.com/user-attachments/assets/2b839739-9c29-488c-9251-f4ad9481e1c1)
![Screenshot (56)](https://github.com/user-attachments/assets/1c38861c-94b2-48e7-8bc8-7bff9383280c)
![Screenshot (55)](https://github.com/user-attachments/assets/1df5d3e1-16d1-453e-9835-f8ade11d3e8c)

3. SQL Database Table
![Screenshot (57)](https://github.com/user-attachments/assets/aac771c8-7b37-48be-85ca-eb6ae9448597)

4. Power BI Dashboard
![Screenshot (58)](https://github.com/user-attachments/assets/75435a5f-a7f3-4385-81c5-1b3397fcf255)


🚀 How to Run the Project

1.Clone the repository:

git clone https://github.com/VishalPawar3696/NBA-Players-Data-Analysis.git

2.Install required libraries:
pip install pandas matplotlib seaborn sqlalchemy pymysql

3.Run the Python files to clean the dataset.

4.Upload cleaned data into your MySQL database.

5.Open Power BI → Connect to MySQL → Load data → Dashboard ready!
