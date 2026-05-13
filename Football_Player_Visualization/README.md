# Football Player Information Visualization

An exploratory data analysis and visualization project examining a dataset of professional football players.

## Overview

This project investigates two central questions:
- **How do player ratings vary by age and position?**
- **How is football talent distributed across countries?**

Findings carry practical implications for scouting strategy, squad planning, and understanding global talent pipelines.

## Files

| File | Description |
|------|-------------|
| `football_analysis.Rmd` | R Markdown source file containing all code and narrative |
| `football_analysis.html` | Rendered HTML report (open in browser to view) |
| `players2.csv` | Source dataset — football player attributes from Kaggle |

## Visualizations

1. **Top Countries by Player Count** — bar chart of the 10 most represented nations
2. **Age vs Overall Rating** — scatter plot by position group
3. **Rating Distribution by Position** — boxplot comparing spread across roles
4. **Skill Heatmap** — average technical attributes per position group
5. **Global Player Distribution** — choropleth map of player counts by country
6. **Country to Position Flow** — alluvial chart linking nationality to position

## Tools & Libraries

- R / R Markdown
- `tidyverse`, `ggplot2`, `scales`
- `sf`, `rnaturalearth`, `rnaturalearthdata`
- `ggalluvial`

## Data Source

[Soccer Players Dataset — Kaggle](https://www.kaggle.com/datasets/cihan063/soccer-players?resource=download)
