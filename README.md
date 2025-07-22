# 📊 Netflix Titles Power BI Dashboard

This project delivers an interactive and data-driven dashboard built in Power BI to analyze Netflix's global content catalog. Leveraging advanced data visualization and transformation techniques, the report provides in-depth insights across multiple dimensions such as:

📂 Genre classification (multi-genre titles using listed_in

🔢 Rating distribution (TV-MA, PG-13, etc.)

🌍 Geographic distribution (country-level breakdowns and filters)

📅 Temporal analysis (release trends across years)

🎞️ Content type split (TV Shows vs Movies)

📈 Interactive filters and cross-highlighting for dynamic data exploration

Built with Power Query for ETL, DAX measures for custom aggregations, and cross-filtering logic, this dashboard enables real-time, drill-down analytics for decision-making and trend identification in streaming data content.

## 📌 Overview

The dashboard provides insights into:
- Total Titles on Netflix
- Locations associated with content
- Ratings distribution
- Genre popularity
- Top contributing countries
- Movie vs. TV Show ratio
- Historical trend of content release

<img width="1633" height="920" alt="image" src="https://github.com/user-attachments/assets/1833666f-4e77-4441-b0eb-76b74e92a5d9" />

## 📁 Dataset

The dataset used is derived from the publicly available from Kaggle, containing:
- Title
- Type (Movie/TV Show)
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genres (`listed_in`)
- Description

## 📈 Dashboard Features

| Metric                          | Description |
|---------------------------------|-------------|
| 🔢 **Total Titles**             | Total number of Netflix titles in the dataset (8802) |
| 🌍 **Locations**               | Number of unique countries represented (749) |
| 🎞️ **Genres**                 | Count of unique genre tags (515) |
| 🏷️ **Ratings**                | 18 total ratings (e.g., TV-MA, PG-13) |
| 📆 **Release Timeline**        | Range from 1925 to 2021 |
| 🍿 **Type Split**             | Distribution between Movies and TV Shows |
| 🎬 **Genre Breakdown**        | Most common genres by title count |
| 🌐 **Top Countries**          | Leading countries contributing content |
| ⏳ **Historical Release Trend**| Title count over release years |

## 📦 Tools Used

- **Power BI Desktop**
- **DAX** for custom measures
- **Power Query** for data transformation
- **Kaggle** for dataset source

## 🚀 Getting Started

To explore or modify the dashboard:
1. Download the `.pbix` file (coming soon).
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop).
3. Load the Netflix dataset or update your data source.
4. Customize visuals, filters, and themes as needed.

## 🧠 Insights

- **TV-MA** is the most common rating.
- The **United States** leads content production.
- **2018–2020** was the most active content release period.
- **Dramas, Documentaries, and Stand-Up Comedy** are the most popular genres.

## 📄 Data visualizations dynamically update upon selecting a filter (country = US)

<img width="1631" height="920" alt="image" src="https://github.com/user-attachments/assets/4d004a6e-df4b-41c5-a349-5bdea1e35064" />


---

