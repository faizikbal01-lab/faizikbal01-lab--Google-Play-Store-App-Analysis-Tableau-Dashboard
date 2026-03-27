# Google Play Store App Analysis — Dashboard Report Looker studio

## Project Overview

The mobile app marketplace is one of the most competitive digital ecosystems in the world, with millions of apps vying for installs, ratings, and user loyalty. This project presents a **visual dashboard analysis** of the **Google Play Store** dataset, covering **9,660+ unique apps** across **34 categories**. The report explores what separates high-performing apps from the rest — examining install volumes, user ratings, review counts, pricing models, content classifications, and app size distributions.

As a **Business and Data Analyst**, the objective is to convert raw Play Store metrics into clear, decision-ready intelligence that helps **app developers, product strategists, and market researchers** prioritize where to invest, how to price, and which audiences to target.

---

## Business & Product Objectives

The analysis seeks to provide data-backed answers to the following critical questions:

1. **Monetization Strategy:** How does the Free vs. Paid split look across the store, and what is the impact on review volume and installs?
2. **Category Landscape:** Which of the 34 app categories dominate the Play Store in terms of app count and audience reach?
3. **Audience Segmentation:** How are apps distributed across content ratings — Everyone, Teen, Mature 17+, and Everyone 10+?
4. **Top App Performance:** Which apps lead in install counts, and what categories do they belong to?
5. **Installs vs. Reviews Correlation:** Is there a meaningful relationship between how many installs an app has and how many reviews it receives?
6. **Size vs. Installs:** Does app size influence install behavior — do lighter apps get downloaded more?

---

## Dataset Description

The dashboard is built on the **Google Play Store** dataset with the following key attributes:

| Feature | Description |
| --- | --- |
| `App` | Name of the application (9,660 unique apps in dataset) |
| `Category` | App category — 34 unique categories (FAMILY, GAME, TOOLS, etc.) |
| `Rating` | Average user rating out of 5.0 *(Overall average: **4.19**)* |
| `Reviews` | Total user review count *(Total across all apps: **4,044,332,969**)* |
| `Size` | App size (used in size vs. installs scatter analysis) |
| `Installs` | Install count bracket (e.g., 10,000+, 1,000,000+) |
| `Type` | Free or Paid |
| `Price` | Price in USD (0 for free apps) |
| `Content Rating` | Audience classification (Everyone, Teen, Mature 17+, etc.) |
| `Genres` | Detailed genre sub-classification |
| `Last Updated` | Date the app was last published to the Play Store |

---

## Dashboard Overview

The report consists of **two pages** of interactive visual analysis:

### Page 1 — Summary Metrics & Audience Breakdown

| Visual | Description |
| --- | --- |
| **KPI — Average Rating** | Overall store average rating: **4.19 / 5.0** |
| **KPI — Total Apps** | **152** apps featured in the filtered view |
| **Category Table** | Ranked list of all **34 categories** (FAMILY ranks #1 by count) |
| **Free vs. Paid Pie Chart** | **92.6% Free** vs. **7.4% Paid** — overwhelming free-app dominance |
| **Content Rating Breakdown** | Everyone: 8,382 · Teen: 1,146 · Mature 17+: 447 · Everyone 10+: 377 · Adults only 18+: 3 · Unrated: 2 |
| **Top Apps by Installs** | Top 5 apps shown: English Grammar Test, Ruler, Period Tracker, Calculator, Call Blocker *(1–5 of 9,660 apps)* |

### Page 2 — Engagement & Distribution Analysis

| Visual | Description |
| --- | --- |
| **KPI — Total Reviews** | Aggregate review count across all apps: **4,044,332,969** |
| **Free vs. Paid Install Bar Chart** | Free apps generate dramatically higher install volumes (~450K+) vs. Paid apps (~10K) |
| **Top Apps by Category (Parallel Coordinates)** | Multi-category comparison of top apps — Bubble Shooter, Solitaire, Word Search, Farm Heroes, Ruler, Blood Pressure, Chess Free, English Grammar, Period Tracker, Call Blocker — across FAMILY, GAME, TOOLS, BUSINESS, LIFESTYLE, SPORTS |
| **Size vs. Installs Scatter Plot** | Explores whether app file size correlates with install behavior by category |
| **Installs vs. Reviews Bubble Chart** | Bubble chart revealing the relationship between install count and review volume — a key proxy for user engagement and app stickiness |

---

## Key Insights (Executive Summary)

- **Free Apps Dominate:** With **92.6% of apps being free**, the Play Store is overwhelmingly driven by a free-to-install model. Paid apps are a small niche — but often serve specialized, higher-intent user segments.
- **Healthy Average Rating:** An overall average rating of **4.19** suggests the store-wide quality bar is reasonably high, but also that ratings alone are not a strong differentiator.
- **Everyone is the Core Audience:** Over **8,382 apps** (the vast majority) carry the "Everyone" content rating — meaning broad, family-safe appeal is the dominant market positioning strategy.
- **Review Volume as Engagement Signal:** With over **4 billion total reviews** across the dataset, review count is a powerful proxy for active user engagement — apps with higher installs don't always have proportionally higher reviews.
- **Top Categories:** FAMILY, GAME, and TOOLS consistently appear as the largest categories by app count, reflecting where developer activity is most concentrated.
- **Install-Review Gap:** The Installs vs. Reviews bubble chart reveals that a small number of breakout apps accumulate disproportionately large review volumes — indicating extreme concentration of engagement at the top of the market.

---

## Tools & Technologies

- **Tableau** — Dashboard creation and interactive visual analytics
- **Data Source:** Google Play Store dataset (`googleplaystore.xlsx`)
- **Visualization Types:** KPI cards, pie chart, ranked tables, bar chart, parallel coordinates plot, scatter plot, bubble chart
- **Report Export:** PDF dashboard snapshot (`Untitled_Report.pdf`)

---
## Recommendations

- **Quantify the install-review concentration:** The insight that "a small number of breakout apps accumulate disproportionately large review volumes" is compelling — strengthen it with a specific figure, e.g. what share of total reviews the top 10 apps account for.
- **Add a `Last Updated` recency analysis:** A bar chart binning apps by update year would add a temporal dimension currently absent from both pages and reveal whether recently updated apps correlate with higher ratings or installs.

---
## Author

**Mohd Faiz**
- **Role:** Business and Data Analyst
- **GitHub:** [hub.com/faizikbal01-lab](https://github.com/your-username)


