# Footwear CPI Analysis

**Student:** Jonathan Zaharia | **Course:** Data Intensive Fundamentals

## Hypothesis
Footwear prices in the U.S. have increased over time, with the sharpest rise occurring after 2000 due to increased consumer demand and supply chain pressures.

## Dataset
- **Source:** FRED (Federal Reserve Bank of St. Louis)
- **Series:** Consumer Price Index for Footwear (CUUR0000SEAE)
- **Coverage:** January 1947 – January 2026 (monthly)

## Files
- "CUUR0000SEAE.csv" — Full raw dataset downloaded via curl
- "footwear.csv" - CUUR0000SEAE.csv uploaded
- "footwear_2000s.csv" — Filtered dataset (2000 onwards) created with awk
