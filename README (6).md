# Rainfall Analysis and Planting Advisory

This project cleans monthly rainfall data for five Kenyan counties (Nairobi, Nakuru, Kisumu, Mombasa and Machakos), analyses it with NumPy and produces a planting advisory for a farmer-support NGO. The hand-typed Machakos data is cleaned first, with invalid entries imputed and documented.

## How to run the notebook

1. Install the dependencies: `pip install -r requirements.txt` (plus `jupyter` to open the notebook).
2. Start Jupyter: `jupyter notebook rainfall_analysis.ipynb`.
3. Choose **Kernel > Restart & Run All**. The notebook regenerates `rainfall_summary.csv` in the same folder.

## Planting advisory

- Nairobi, Nakuru, Kisumu and Mombasa should plant in **April-May**, when the long rains give the highest two-month rainfall.
- Machakos should plant in **November-December**, using the short rains, and should prefer drought-tolerant varieties because it has 6 dry months.
- Machakos figures include two estimated months (April and September), so confirm this advice with local extension officers.
