# Dynamic Parking Pricing – Summer Analytics 2025

**Name:** Shivam Kansal  
**Email:** shivam427kansal@gmail.com  
**Program:** Summer Analytics Capstone, 2025

---

## Project Overview

This project focuses on building a dynamic pricing engine for urban parking lots. The idea is to simulate how parking prices can adjust in real-time using data like occupancy levels, traffic conditions, vehicle type, and queue length.

Three pricing models were developed and compared to observe different strategies for setting parking fees.

---

## Tech Stack

- Python (Pandas, NumPy)
- Google Colab (code execution)
- Bokeh (for plotting price behavior)
- GitHub (for version control)

---

## Pricing Models

### 🔹 Model 1 – Linear Occupancy-Based Pricing  
Simple model where the price increases linearly with how full the lot is.  
Formula used: `Price = Base + α × OccupancyRate`

### 🔹 Model 2 – Demand-Based Pricing  
Takes multiple real-world features into account like:
- Occupancy Rate  
- Queue Length  
- Traffic Conditions  
- Special Days  
- Vehicle Type  
A combined demand score is normalized and used to adjust prices dynamically.

### 🔹 Model 3 – Competitive-Based Pricing  
This model checks nearby parking lots (within 500m) and adjusts prices based on their rates.  
If neighbors are cheaper and queues are long, prices are reduced.  
If neighbors are expensive, prices may be increased slightly.

---

## Visualization

A comparison of all three models was plotted using Bokeh.  
The plot shows how pricing changes throughout the day for a selected lot.

---

## Repository Contents

- `Dynamic_Pricing_Urban_Parking_SummerAnalytics2025.ipynb` – main notebook with all logic
- `Architecture.png` – block diagram showing model flow
- `model_comparison_plot.png` – Bokeh plot comparing all 3 models
- `stream_output_model2.png` – sample simulated print output for Model 2
- `README.md` – this file

---

## How to Run

1. Open the notebook in Google Colab  
2. Upload the dataset file when prompted  
3. Run all cells in order  
4. Final output includes:
   - Price columns from all three models  
   - Bokeh plot for comparison  
   - Optional simulated streaming printout

---

## Conclusion

This project helped explore how data-driven pricing strategies can be built and compared using real urban parking data.  
It involved:
- Feature engineering  
- Multiple pricing logics  
- Comparison through plots  
- Basic simulation for final output

Thank you for reviewing this project.
