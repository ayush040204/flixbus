# Flixbus Price Flagging System

This notebook identifies pricing anomalies in Flixbus bus listings by comparing 
Flixbus prices against median prices of similar buses.

## Similarity Parameters
- Same Route
- Same Date  
- Same AC Status
- Same Sleeper/Seater Status
- Departure time within ±2 hours

## Flagging Logic
- Too High: Price > 20% above median
- Too Low: Price > 20% below median
- OK: Within ±20% of median

## Tools Used
- Python
- Pandas
- Jupyter Notebook
