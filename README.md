# Spotify End-to-End Data Analysis Project 🎵
## Project Overview
This project provides a comprehensive analysis of Spotify streaming data, transformed and visualized using Power BI. The goal was to build an end-to-end pipeline that converts raw music data into actionable insights, focusing on artist performance, track popularity, and user listening patterns.

## Key Features
Dynamic Dashboard: Interactive visuals allowing users to filter by Year, Genre, and Artist.
KPI Tracking: Real-time tracking of Total Streams, Average Popularity, and Energy Levels.
Trend Analysis: Visualization of streaming trends over time to identify seasonal peaks.
Artist Deep-Dive: Comparative analysis of top artists based on followers and track count.

## Technical Stack
Tool: Power BI Desktop
Data Source: Spotify Dataset (Kaggle/API)
Data Processing: Power Query (M Language)
Modeling: DAX (Data Analysis Expressions) for custom measures

## Workflow
Data Extraction: Imported raw CSV/JSON data into Power BI.
Data Transformation (ETL): * Cleaned missing values and handled duplicates using Power Query.
Unpivoted columns for better time-series analysis.
Formatted data types for optimized performance.
Data Modeling: Created a star schema to establish relationships between tracks, artists, and time dimensions.
DAX Calculations: Developed custom measures for:
Total Streams = SUM(Spotify[Streams])
Growth Rate % = (Current - Previous) / Previous
Data Visualization: Designed a user-centric UI with a "Dark Mode" theme to match the Spotify brand identity.

## Key Insights
Genre Dominance: Identified which genres maintained the highest average popularity scores.
Audio Features: Explored the correlation between "Danceability" and "Stream Count."
Top Performers: A ranked list of the most influential artists within the dataset period.

## How to View
Download the .pbix file from this repository.
Open it using Power BI Desktop
