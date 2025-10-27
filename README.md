# Exploring Cross Platform App Market Data  
### A Dataquest Guided Project

This project analyzes datasets from both the Apple App Store and Google Play Store to identify which types of free apps attract the most users. The work focuses on understanding app genre trends, user ratings, and install counts to help guide data-driven decisions about future app development.

---

## Project Overview

Our company develops free Android and iOS apps supported by in-app advertisements. Because revenue depends on the number of active users, the goal is to determine which app profiles are likely to attract the largest audiences on both platforms.

This project aims to:
- Explore the distribution of app genres across both markets  
- Identify patterns in user engagement and installs  
- Recommend an app genre that shows potential for success in both ecosystems

---

## Analysis Outline

1. **Data Cleaning**  
   - Removed duplicate and invalid rows  
   - Filtered datasets to include only free, English-language apps

2. **Exploratory Analysis**  
   - Reviewed app genre frequencies  
   - Calculated average user ratings (`rating_count_tot`) for App Store genres  
   - Calculated average installs for Google Play categories

3. **Findings**  
   - **App Store:** Reference, Music, and Weather apps had the highest average total ratings, indicating broad user engagement.  
   - **Google Play:** Communication, Productivity, and Books & Reference apps recorded strong average installs.  
   - Across both platforms, practical apps with recurring use patterns tend to perform better than entertainment-heavy genres.

4. **Recommendation**  
   A Reference or Productivity app that provides quick, reliable information or supports recurring daily tasks is the most promising direction for cross-platform success.  
   These genres demonstrate consistent engagement without relying on social or entertainment trends.

---

## Key Takeaways

- Large install averages often reflect a few dominant apps rather than broad popularity across the category.  
- Practical and utility-based apps generally attract stable, repeat engagement on both stores.  
- Focusing on daily-use, information-driven functions may yield the best long-term growth for a free, ad-supported model.

---

## Tools and Environment

- **Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries:** `csv`, built-in Python utilities (and optionally `pandas`)  
- **Datasets:** Provided by Dataquest (AppleStore.csv and googleplaystore.csv)

---

## Repository Structure

```text
├── app_analysis.ipynb
├── docs/
│   └── index.html
├── data/
│   ├── AppleStore.csv
│   └── googleplaystore.csv
└── README.md
```
