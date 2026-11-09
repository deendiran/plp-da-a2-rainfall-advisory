# Rainfall Pattern Analysis & Planting Advisory

## Project Summary
This project analyzes monthly rainfall patterns across five Kenyan counties (Nairobi, Nakuru, Kisumu, Mombasa, and Machakos) for a farmer-support NGO. Raw station data containing corrupted values was cleaned and imputed, followed by vectorized NumPy analysis to determine annual totals, wettest months, dry-month risks, and optimal two-month planting windows.

## How to Run the Notebook
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/plp-da-a2-rainfall-advisory.git
   cd plp-da-a2-rainfall-advisory
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook rainfall_analysis.ipynb
   ```
4. Run all cells from top to bottom (**Kernel -> Restart & Run All**).

## Planting Advisory
* Smallholders in Nairobi, Nakuru, Kisumu, and Mombasa should target the high-volume April–May window to maximize crop establishment.
* Farmers in Machakos should focus planting operations on the October–November short rains to avoid mid-year drought risks.
* Given that Nairobi and Machakos face five dry months annually, farmers in these counties must prioritize soil moisture conservation and drought-resistant seed varieties.
