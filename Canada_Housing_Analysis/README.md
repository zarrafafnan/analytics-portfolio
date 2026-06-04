# Canadian Housing Price Index Analysis (1981-2022)

## Overview
An exploratory data analysis of Canada's Housing Price Index (HPI) across major regions from 1981 to 2022, using Python. The project investigates long-term national trends, regional comparisons, and the impact of key economic events including the 1989 bubble, the 2008 financial crisis, and the COVID-19 housing surge.

## Dataset
- **Source:** Canada Mortgage and Housing Corporation (CMHC)
- **Coverage:** Monthly HPI data by province and city, 1981-2022
- **Property Type:** House and Land (filtered from multi-type dataset)

## Tools & Libraries
- Python 3
- pandas
- matplotlib

## Questions Answered

**Q1. How has Canada's national HPI trended over 40 years?**
Canadian HPI nearly tripled from ~40 in 1981 to ~128 in 2022. Two notable crashes are visible: the late 1980s bubble burst (1991) and the 2008 financial crisis. The post-2020 COVID surge was the sharpest in the dataset's history.

**Q2. How do Toronto, Vancouver, and Alberta compare over time?**
Vancouver consistently led in HPI from 1981, driven by early demand and two major boom-bust cycles. Alberta's surge between 2005-2008 directly tracks the oil boom, followed by a sharp decline when oil prices fell. All three regions converged sharply post-2020, suggesting the COVID-era housing surge erased historical regional differences in price levels.

**Q3. Which region had the biggest post-2020 (COVID-era) price surge?**
Vancouver saw the largest HPI increase post-2020 (+22.7 points), followed closely by Alberta (+21.2 points). Toronto's surge was smaller (+13.5 points), likely because it was already at a high baseline before COVID. Alberta's strong surge is notable given its flat/declining period since 2008, suggesting renewed demand driven by interprovincial migration from expensive Ontario and BC markets.

**Q4. What does Toronto's year-over-year HPI growth rate reveal?**
Toronto's sharpest growth occurred during the late 1980s housing bubble, peaking at ~27% year-over-year, followed by a dramatic crash to -15% in 1991 when high interest rates burst the bubble. From the mid-1990s onward, growth stabilized at a modest 2-5% annually. The post-2020 surge reached ~7% before declining in 2021-2022, confirming a year-over-year price drop as the market cooled after the COVID spike.

## Files
- canada_housing_analysis_portfolio.ipynb: full analysis notebook with code, charts, and findings
- `HPI_1981-2022_by_regions.csv`: raw dataset

## Key Takeaways
- Alberta's housing market is uniquely tied to oil prices which is a direct signal for anyone tracking Calgary's economy
- The COVID-era surge was unprecedented in speed, affecting all regions equally regardless of prior price levels
- Toronto and Vancouver, despite their reputation as expensive markets, did not surge as dramatically as Alberta post-2020 suggesting affordability-driven migration reshaping demand across Canada

