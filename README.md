## Overview
This sample project analyzes deforestation events in **2025** to identify concessions likely to continue clearing in **January 2026**.
It detects:
- Ongoing monthly deforestation trends  
- Spatial clustering of clearing activity  
- Concessions with higher continuation risk  

## Method
- Filter events where **After Date = 2025**
- Keep records with **1–3 month duration**
- Aggregate monthly deforestation per concession
- Project January 2026 area using trend analysis
- Rank concessions by predicted area and spatial continuity

Top 5 highest-risk concessions are visualized.

## Limitations
- Uses simple linear trend projection  
- Does not include policy, market, or enforcement drivers  
- Based only on 2025 data  
This model functions as an early-warning screening tool.

## Interactive Map
View the spatial risk map:
**https://cholidasofi.github.io/deforestation-prediction-analysis/**

The map displays:
- Top 5 predicted concessions  
- Risk classification (Low / Medium / High)  
- Predicted deforestation area for January 2026  
