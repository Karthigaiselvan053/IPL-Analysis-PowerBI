# IPL Analysis Dashboard \| Power BI

## Project Overview

This project is an interactive **IPL Analysis Dashboard** built using
**Power BI** to analyze IPL data from **2008 to 2026**.

The dashboard provides a visual overview of team performance, player
statistics, match information, and season-wise insights. Users can
select a season and explore the corresponding KPIs, top performers,
points table, and match details.

## Dashboard Highlights

-   Season-wise IPL analysis from 2008--2026
-   Champion and Runner-up information
-   Toss-winning team and toss decision
-   Total matches and participating teams
-   Total 4s and 6s
-   Centuries and half-centuries
-   Orange Cap statistics
-   Purple Cap statistics
-   Top players for boundaries
-   Season-wise points table
-   Team logos and player images
-   Interactive season filter

## Data Model

The Power BI model contains the following main tables:

-   `ipl_matches_data` -- match-level information such as season, city,
    venue, match type, date, and teams
-   `ball_by_ball_data` -- ball-by-ball information including batter,
    bowler, runs, extras, and match details
-   `teams_data` -- team names, short names, and team image URLs
-   `players-data-updated` -- player details, images, batting style,
    bowling style, and player IDs

The model uses relationships between match, team, ball-by-ball, and
player data to build the dashboard.

## Key Analysis

### Team Analysis

-   Champion and Runner-up
-   Season-wise team participation
-   Wins, losses, ties and no-results
-   Points table
-   Team performance comparison

### Player Analysis

-   Orange Cap
-   Purple Cap
-   Top four hitters
-   Top six hitters
-   Centuries
-   Half-centuries

### Match Analysis

-   Total matches
-   Venues
-   Toss-winning team
-   Toss decision
-   Match and season-level statistics

## Tools & Technologies

-   Power BI
-   Power Query
-   DAX
-   Data Modeling
-   Data Visualization
-   Excel / CSV data sources


## Project Structure

IPL-Analysis-PowerBI/
│
├── IPL_Analysis.pbix
├── README.md
│
├── IPL Data/
│   ├── ball_by_ball_data.xlsx
│   ├── ipl_matches_data.xlsx
│   ├── players-data-updated.xlsx
│   └── teams_data.xlsx
│
├── images Used/
│   ├── Cricbuzz-Logo
│   ├── IPL-Logo
│   ├── Facebook_Logo
│   ├── Instagram_icon
│   ├── X-logo
│   ├── Orange Cap
│   ├── Purple Cap
│   ├── tata-ipl-logo
│   └── Youtube_logo
│
└── data (2026)/
    └── [2026 IPL data files]

## How to Use

1.  Download or clone this repository.
2.  Open `IPL_Analysis.pbix` using Power BI Desktop.
3.  Refresh the data if required.
4.  Use the season slicer to explore different IPL seasons.
5.  Interact with the dashboard visuals to analyze team and player
    performance.

## Skills Demonstrated

-   Data Cleaning and Transformation
-   Power Query
-   DAX Measures
-   Data Modeling
-   Relationship Management
-   KPI Design
-   Interactive Dashboard Development
-   Sports Data Analysis
-   Data Visualization

## Author

**Karthigaiselvan E**

B.Tech -- Information Technology\
Data Analytics \| SQL \| Power BI \| Excel \| Python

## Connect

If you find this project useful, feel free to explore the repository.
