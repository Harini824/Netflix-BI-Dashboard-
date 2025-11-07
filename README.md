Project Title:
Netflix Movies and TV Shows Analysis Dashboard (Power BI)
🎯 Objective:

To analyze the Netflix content library using data visualization techniques in Power BI, uncovering key insights about genres, ratings, countries, and release trends.
This dashboard aims to help understand what type of content dominates Netflix, how it has grown over time, and which regions and genres contribute the most.

🧩 Dataset Used:

Dataset Name: Netflix Titles Dataset

File: netflix_titles_cleaned.csv

Source: Kaggle / Netflix dataset

Records: 8,800+ titles

Fields Included:

show_id – Unique ID for each title

type – Movie or TV Show

title – Title of the content

director – Director name

country – Country of production

date_added – Date added to Netflix

release_year – Year of release

rating – Audience rating (TV-MA, TV-14, PG, etc.)

listed_in – Genre categories

⚙️ Process Followed:
1. Data Cleaning (Python / Power Query)

Removed duplicates and null values

Standardized text to lowercase

Converted date_added to YYYY-MM-DD format

Extracted key columns relevant for analysis

2. Data Modeling

Imported the cleaned dataset into Power BI

Created calculated measures using DAX:

Total Titles

Total Ratings

Start Year

End Year

Total Genres

Total Countries

3. Dashboard Design

Used dark red theme (Netflix-inspired)

Created KPIs, bar charts, donut charts, line graphs, and treemaps

Added slicers and filters for dynamic interactivity

Implemented bookmarks, drill-through pages, and tooltips

4. Forecasting

Used Power BI’s Analytics → Forecast feature to predict future content growth trends.

💡 Key Questions Answered:

How many total titles are available on Netflix?
→ 8,802 titles across all genres and formats.

Which genres have the most content?
→ Dramas, Documentaries, and Comedies lead the chart.

Which countries contribute the most to Netflix content?
→ The United States, India, and the United Kingdom are the top contributors.

What is the distribution between Movies and TV Shows?
→ Movies make up around 70% of total titles, TV shows 30%.

How has content production changed over the years?
→ A sharp increase in new titles from 2015–2020.

Which ratings dominate Netflix?
→ TV-MA and TV-14 are the most common ratings.

📊 Insights Gained:

Netflix has grown rapidly in recent years, especially after 2015.

The majority of content comes from the United States and India.

Dramas and Documentaries dominate the genre categories.

TV-MA rated content is the most popular classification.

Movies are released more frequently than TV shows.

🛠️ Tools & Technologies Used:

Power BI Desktop – Dashboard creation and visualization

Python / Power Query – Data cleaning and preprocessing

Microsoft Excel – Data verification

🚀 Conclusion:

The Netflix Dashboard provides a clear, visual understanding of Netflix’s content trends and strategies.
It highlights genre diversity, regional production patterns, and content growth, helping users and analysts make data-driven insights about the streaming platform.  
