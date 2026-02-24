# 🍝 Market Entry Strategy — Italian Food in NYC

## Overview

A data-driven consulting project analyzing the **Italian restaurant landscape in Manhattan** to develop a go-to-market strategy for an Italian food company launching its first flagship store in New York City.

This project was completed as part of a **university consulting course at LUISS Guido Carli** (Master's in Data Science and Management), in collaboration with a team of 6 students.

## Business Challenge

An Italian food company — known for pre-cooked meals, cured meats, and bread — wanted to expand into the U.S. market with a physical store in NYC. Two key questions needed answering:

1. **Where** should the first flagship store be located?
2. **What** type of service and products should be offered?

## Approach

### 1. AS IS Assessment — Market Analysis
- Analyzed **172 Italian restaurants** across Manhattan using Zagat-rated scores (Food, Decor, Service) and pricing data
- Segmented the market into 4 categories: Pizzeria, Restaurant, Street Food, Panini
- Built a **linear regression model** to identify price drivers → Decor (+$1.93/point) and Food (+$1.00/point) emerged as the main factors

### 2. Focus on the Offering — Value Proposition
- Proposed a **hybrid "gastronomia" concept** combining three experiences: **Eat** (panini & hot meals), **Drink** (aperitivo bar), and **Shop** (Italian deli/grocery)
- Defined competitive positioning using Food vs. Decor scatter plot against existing Manhattan competitors

### 3. Action Plan — Go-to-Market Strategy
- **Place**: Recommended **SoHo** based on low competition (only 4 Italian restaurants), high foot traffic, and mixed-use demographics (workers + residents)
- **Price**: Set at ~$55-60 for lunch for two, ~$60-65 for aperitivo for two
- **Promotion**: Geo-targeted ads, influencer partnerships, tasting events, cooking classes
- Developed detailed **customer personas** for lunch crowd and evening crowd segments
- Conducted **SWOT analysis** and competitive benchmarking

## Tech Stack

| Tool | Usage |
|------|-------|
| **Python** | Data analysis & visualization |
| **pandas** | Data manipulation |
| **matplotlib / seaborn** | Charts and visualizations |
| **folium** | Geospatial mapping |
| **statsmodels** | Linear regression |
| **PowerPoint** | Final presentation deck |

## Repository Structure

```
├── data/
│   └── nyc_italian_restaurants.csv    # Dataset: 172 Italian restaurants in Manhattan
├── notebooks/
│   ├── 01_market_analysis.ipynb       # EDA, segmentation, regression analysis
│   └── 02_geospatial_analysis.ipynb   # Mapping & neighborhood analysis
├── docs/
│   └── presentation.pdf               # Final consulting deck (30+ slides)
└── README.md
```

## Key Findings

- **Pizzerias dominate** Manhattan's Italian food scene (54.7%), while Panini shops have the highest average scores across all dimensions
- **Decor is the #1 price driver** — investing in ambiance pays off more than food quality alone in terms of pricing power
- **SoHo is underserved** — only 4 Italian restaurants despite high foot traffic and affluent demographics
- A **hybrid format** (deli + restaurant + bar) creates a competitive moat that's hard to replicate

## Team

University group project — LUISS Guido Carli, Master's in Data Science and Management (2025)

## License

This project is shared for educational and portfolio purposes.
