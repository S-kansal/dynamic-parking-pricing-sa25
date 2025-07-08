# Dynamic Parking Pricing – Summer Analytics 2025

Name: Shivam Kansal  
Email: shivam427kansal@gamil.com  
Program: Summer Analytics Capstone, 2025

## Project Overview

This project focuses on building a dynamic pricing engine for urban parking lots. The goal is to simulate real-time pricing based on various features such as occupancy, queue length, traffic conditions, and vehicle types.

Three models were created to observe different pricing strategies and simulate their behavior using streaming data.

## Tech Stack

- Python (Pandas, NumPy)
- Bokeh (for visualization)
- Pathway (for real-time stream simulation)
- Google Colab (execution)
- GitHub (version control)

## Pricing Models

### Model 1 – Linear Pricing
Basic model where price increases linearly with occupancy rate.  
Formula: `Price = Base + 2 × OccupancyRate`

### Model 2 – Demand-Based Pricing
Pricing depends on multiple features like traffic, queue length, special day indicator, and vehicle type. A normalized demand score is used to adjust the price.

### Model 3 – Competitive Pricing
Price is adjusted based on nearby parking lots. If nearby lots are cheaper or expensive, prices are adjusted accordingly to stay competitive.

## Streaming Simulation

Pathway was used to simulate the models in a real-time environment.  
The system outputs updated prices for all parking lots across time intervals, simulating real-world conditions.

## Repository Contents

- `Dynamic_Pricing_Urban_Parking_SummerAnalytics2025.ipynb` – main code notebook
- `pathway_output.jsonl` – output from streaming Model 1
- `pathway_output_model2.jsonl` – output from streaming Model 2
- `README.md` – this file

## How to Run

1. Open the notebook in Google Colab  
2. Run all the cells in order  
3. Bokeh plots will display price changes  
4. Streaming outputs will appear in the console and be saved as `.jsonl` files

## Conclusion

This project helped build an understanding of demand-based pricing systems using real-time data.  
It involved data preprocessing, feature engineering, model building, and live simulation using Pathway.  
The visualizations and outputs provided insights into how prices change with different real-world factors.

Thank you for reviewing this submission.
