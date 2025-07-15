#**Amazon-prime-dashboard**
📊 Amazon Prime Video Dashboard (Excel + Power BI)
<img width="1316" height="738" alt="image" src="https://github.com/user-attachments/assets/3780774b-6d9d-491d-84ed-a7664aa0df4a" />


Image Description

🔍 Project Overview This project presents a comprehensive dashboard of Amazon Prime Video content from 1920 to 2021 using Excel for data preprocessing and Power BI for dashboard creation. It showcases insights on genres, ratings, release trends, countries, and movie vs TV show distributions.

🧹 Data Cleaning & Transformation (Excel) The raw dataset was cleaned and transformed in Excel using the following steps:

Remove duplicates & blanks: Cleaned titles, ratings, genres, and country columns.

Split multi-valued fields: Genres, Directors, and Countries were split using text-to-columns and Power Query functions.

Date parsing: Extracted release year from date fields.

Data type correction: Converted text to numbers and corrected date formats.

New column creation: Added columns for:

Type: Movie or TV Show

Release Year

Primary Genre

Rating Category

📊 Power BI Dashboard The cleaned Excel file was imported into Power BI, where the dashboard was created with the following visuals:

KPI Cards Total Titles: 9655
Total Ratings: 25

Total Genres: 519

Total Directors: 5771

Start Date: 1920

End Date: 2021

Bar Charts Ratings by Total Shows
Genres by Total Shows

Map Total Shows by Country (using Filled Map visual)

Donut Chart Movie vs TV Show Distribution:

TV Shows: 7.81K (80.82%)

Movies: 1.85K (19.18%)

Line Graph Total Shows by Release Year (1920–2021) split by Type
💡 Key Insights The most popular genre is Drama, followed by Comedy.

The majority of content is targeted at the 13+ and 16+ age groups.

TV Shows dominate the platform, comprising over 80% of the content.

The largest spike in content release occurred after 2015, with exponential growth in titles.
