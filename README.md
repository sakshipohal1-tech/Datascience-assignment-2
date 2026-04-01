# Data_science_assigment2
Movie Data Analysis using Python (Google Colab) - Assignment
🎬 Movie Data Analysis Project

👩‍💻 Author

Ishant Pal B.Tech Computer Science Engineering

📌 Project Overview

This project focuses on analyzing a dataset of 3000 movies to help a movie producer make data-driven decisions about:

What type of movies to produce
Which actors to cast
Which directors and producers perform best
The analysis is based on profitability, ROI (Return on Investment), genres, and actor/director performance.

📊 Objectives

The main objectives of this project are:

Identify the most profitable movie and analyze its cast and crew
Determine which language yields the highest average ROI
Explore all unique movie genres
Analyze producers and directors based on ROI
Identify the most active actor and analyze their performance
Study director preferences for actors
📂 Dataset Description

The dataset contains details of approximately 3000 movies, including:

Movie Title
Budget
Revenue
Profit
ROI (Return on Investment)
Language
Genre
Cast (Actors)
Director
Producer
🔍 Data Preprocessing

Before analysis, the dataset was cleaned and validated:

Removed missing or null values
Checked for duplicate entries
Converted data types (budget, revenue, profit)
Calculated Profit and ROI where required
📈 Analysis & Insights

1️⃣ Highest Profit Movie

Identified the movie with the maximum profit

Extracted:

Producer
Director
Actors
2️⃣ Language with Highest ROI

Grouped data by language
Calculated average ROI
Identified the most profitable language
3️⃣ Unique Genres

Extracted all distinct genres
Analyzed diversity of movie types
4️⃣ Top Producers by ROI

Created a table of:

Producers
Directors
Calculated average ROI per producer

Identified Top 3 producers

5️⃣ Most Frequent Actor Analysis

Found the actor appearing in maximum movies

Deep analysis:

Number of movies
Genres
Profit trends
6️⃣ Director-Actor Preferences

Analyzed which actors are most frequently cast by top 3 directors
Identified collaboration patterns
⚙️ Technologies Used

Python
Pandas
NumPy
Matplotlib / Seaborn (for visualization)
Jupyter Notebook
🚀 How to Run the Project

Clone or download this repository

Open the notebook file in Jupyter Notebook

Install required libraries:

pip install pandas numpy matplotlib seaborn
Run all cells to reproduce results

📊 Key Insights

High ROI movies are not always high budget
Certain languages dominate profitability
Some actors consistently appear in successful films
Director-actor collaborations influence performance
📌 Conclusion

This analysis helps producers make data-driven decisions by identifying:

Profitable movie types
Successful actors and directors
High-performing languages and genres
⭐ Future Improvements

Add machine learning model to predict movie success
Include audience ratings and reviews
Perform sentiment analysis
📌 Note

This project is created for academic and learning purposes as part of Data Science coursework.

🙌 Acknowledgement

Project developed and analyzed by Ishant Pal
