# Actual Sales vs Target Sales Dashboard

An interactive Power BI dashboard that tracks sales performance against targets across products, months, regions, and sales representatives (2022–2023).




## Business Problem
Does the company meet its sales targets? Which regions, months, and sales reps are over- or under-performing, and where should management focus?

## Dataset
- **Source:** Practice (training) dataset
- **Period:** 2022 – 2023
- **Main fields:** Region, Sales Rep, Sales Team, Product Name, Month, Year, Actual Sales, Sales Target

## Tools Used
Power BI (DAX, matrix, slicers, combo charts) | Excel

## What I Did
1. Cleaned and modeled the sales data
2. Created measures: **Sales Target Achieved (%) = Actual Sales / Sales Target**
3. Built KPI cards for Actual Sales, Target, and Achievement %
4. Built combo charts (columns + line) by product and by month
5. Built a Region → Sales Rep matrix with color-coded achievement by month
6. Added slicers for Year, Month, Product, and Sales Team

## Key Insights
- Total actual sales reached **5.31M** against a target of **5.34M**, an overall achievement of **99.3%**.
- By region, **South** hit **100.0%**, **East** 99.2%, and **North** was lowest at **98.0%**.
- **December (102.0%)** and **July (101.5%)** were the strongest months, while **September (97.5%)** was the weakest.
- A few individual results stand out as outliers: one rep in East reached **239%** in November but only **30.8%** in March; one rep in North recorded **21.5%** in December.

## Recommendations
- Focus support and coaching on the **North** region, which is consistently below target.
- Investigate the extreme monthly results to confirm whether they come from target-setting issues or data errors.
- Review targets for weaker months such as September to make them more realistic.
- Learn from the high-performing months (July, December) and replicate their drivers.

## Notes
This project uses a practice dataset and is intended to demonstrate dashboard design and analysis skills.
