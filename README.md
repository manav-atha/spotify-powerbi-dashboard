# 🎵 Spotify Power BI Dashboard

An interactive Spotify analytics dashboard built using Microsoft Power BI to explore songs, artists, popularity, release trends, album types, and other track-level characteristics.

This project was completed as a hands-on Power BI learning project based on an end-to-end Spotify dashboard tutorial, with a focus on developing both analytical and creative dashboard-building skills.

---

## 📊 Project Overview

The dashboard provides an interactive view of Spotify track data through multiple pages:

- **Home** — Dashboard landing page and navigation
- **Overview** — High-level KPIs and Spotify trends
- **Artists** — Artist-level analysis and performance
- **Songs** — Song-level analysis and popularity

The dashboard allows users to explore the data using interactive navigation, slicers, filters, and visual elements.

---

## 🎯 Key Metrics

The main dashboard KPIs include:

| KPI | Value |
|---|---:|
| Distinct Songs | 789 |
| Distinct Artists | 342 |
| Average Duration | 3.28 min |
| Average Popularity | 89.62 |

---

## 🔍 Analysis Covered

The dashboard explores:

- Most frequently appearing artists
- Songs with the highest popularity
- Artist popularity and song counts
- Position-based song hits
- Average popularity by album type
- Songs by year
- Songs by month
- Monthly average popularity
- Album vs. single distribution
- Explicit vs. non-explicit tracks
- Song duration and other track-level metrics

The interactive design allows users to move between artist-level and song-level analysis while exploring different sections of the dataset.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Dashboard development and visualization
- **DAX** — Measures, calculations, and analytical metrics
- **Power Query** — Data preparation and transformation
- **CSV / Excel** — Data source and data handling
- **Git & GitHub** — Version control and project documentation
- **ChatGPT** — Used to accelerate the creation of DAX measures and support the development process

---

## 🎨 Dashboard Design

A major focus of this project was experimenting with creative Power BI dashboard design rather than relying only on standard visuals.

Design techniques explored include:

- Custom page layouts
- Interactive navigation buttons
- Different button states for normal, hover, and selected conditions
- Image-based song and album displays
- Custom-styled slicers
- Interactive dropdown-style selections
- Spotify-inspired visual design
- Custom navigation between dashboard pages

These techniques helped me understand how Power BI can be used not only for analysis, but also for building more engaging and user-friendly analytical interfaces.

---

## 📷 Dashboard Preview

### Overview

![Spotify Power BI Dashboard](Screenshots/Screenshot%202026-03-01%20171118.png)

### Artists Analysis

![Artists Analysis](Screenshots/Screenshot%202026-03-01%20172032.png)

### Songs Analysis

![Songs Analysis](Screenshots/Screenshot%202026-03-01%20172428.png)

### Home Page

![Dashboard Home](Screenshots/Screenshot%202026-03-01%20173301.png)

Additional screenshots are available in the `Screenshots` folder.

---

## 📁 Dataset

The project uses a Spotify track dataset containing **27,800 records** and information including:

- Song
- Artist
- Spotify popularity
- Chart position
- Date
- Duration
- Album type
- Total tracks
- Release date
- Explicit content
- Album cover URL

The dataset covers Spotify chart data from **May 2023 to November 2024**.

Dataset:

`Data/spotify-top-50-world.csv`


---


## 📚 What I Learned

This project helped me strengthen my practical understanding of Power BI, particularly:

- Creating and using DAX measures
- Data preparation and transformation
- Building interactive dashboards
- Designing custom navigation systems
- Working with slicers and filters
- Creating interactive button states
- Using images and custom layouts in Power BI
- Presenting analytical information through visual storytelling

I also explored how AI tools such as ChatGPT can be used to speed up repetitive DAX development while still requiring the user to understand and validate the resulting measures.


---


## 📂 Repository Structure

```text
spotify-powerbi-dashboard/
│
├── Assets/
│   └── Dashboard design assets
│
├── Data/
│   └── spotify-top-50-world.csv
│
├── Screenshots/
│   └── Dashboard screenshots
│
├── Spotify_analysis_project.pbix
│
└── README.md


