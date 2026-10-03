Amazon Prime TV Shows & Movies Content Analysis Type Prediction

Objective: 
Explore and analyze the Amazon Prime catalog dataset to understand the distribution, trends, 
and insights across movies and TV shows, genres, ratings, countries, and release periods. 
Section A: Data Understanding & Cleaning 

This project covers to answer these following Tasks

Data Loading & Initial Exploration 
● Load the dataset using pandas. 
● Display the first 10 rows. 
● Check the number of rows and columns. 
● Use .info() and .describe() to understand data types and basic stats. 

Data Cleaning 
● Check and handle missing values. 
● Convert date columns to datetime format. 
● Standardize text formatting in categorical columns (e.g., title, genre, type). 
● Remove duplicates (if any). 
Deliverables: 
● Summary of data cleaning steps 
● Cleaned dataset 
Section B: Univariate Analysis 

 Content Types 
● Count of Movies vs TV Shows. 
● Bar chart of content type distribution. 

Release Year 
● Distribution of content across release years. 
● Line or bar chart showing number of releases over time. 

Genre Distribution 
● Most common genres. 
● Create a bar chart of the top 10 genres. 

Ratings 
● Frequency of different content ratings (e.g., TV-MA, PG-13). 
● Pie chart or horizontal bar plot. 
Deliverables: 
● Plots + interpretation of single-variable distributions 
Section C: Bivariate Analysis 

Content Type by Rating 
● Grouped bar plot of rating distribution split by Movies and TV Shows. 

Genre by Type 
● Which genres are more dominant in Movies vs TV Shows? 

Country-wise Analysis 
● Top 10 countries with the most content. 
● Filter by Movies and TV Shows separately. 

Year vs Genre Heatmap 
● Create a heatmap of number of shows/movies released per genre per year. 
Deliverables: 
● Grouped bar plots / stacked charts / heatmaps + written insights 
Section D: Time-Based Trends 

Content Release Over Time 
● Create a time series line plot of releases per year. 
● Split by content type (Movies vs TV Shows). 

Rating Trends Over Time 
● How has the distribution of ratings changed over the years? 
Deliverables: 
● Time series visualizations + interpretation 
Section E: Advanced Grouping & Insights 

Most Frequent Directors & Actors 
● Top 10 most credited directors. 
● Top 10 most frequent actors (if actor column exists). 

Content Duration Analysis 
● Distribution of duration for Movies (in minutes) and TV Shows (seasons or episodes). 
● Outliers or unusually long/short durations? 

Keyword Analysis in Titles (Bonus) 
● Create a word cloud of the most common words in titles. 
● Analyze most common genres in titles containing words like "Love", "War", or 
"Christmas". 
Section F: Summary & Business Recommendations 

Key Findings 
● Write 5–7 bullet-point insights from your analysis. 

Recommendations for Amazon Prime 
● Content type strategy (Movies vs Shows) 
● Region-based acquisition 
● Genre-focused production (based on trends) 
● Content rating considerations 
Optional Bonus Section 

Dashboard (Intermediate) 
● Build a simple interactive dashboard using: 
○ Plotly Dash 
○ Streamlit 
○ Tableau / Power BI 

Predictive Modeling (Advanced) 
● Can you build a model to predict content type (Movie or TV Show) based on other 
attributes (e.g., duration, genre, rating)? 
