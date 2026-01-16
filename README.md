# Credit Risk Modeling with Transition Matrices & Stress Testing

This project builds an end-to-end credit risk analytics framework for a hypothetical bank using 10-year borrower rating data. It applies rating transition matrices to estimate year-wise Probability of Default (PD), Expected Credit Loss (ECL), and cumulative portfolio default risk, and extends the model with stress-testing scenarios.

## Key Objectives
- Analyze portfolio structure and rating migrations using data-driven EDA.
- Construct yearly transition matrices (Years 2–10).
- Compute:
  - Rating-wise and portfolio PDs  
  - Rating-wise and portfolio ECL using LGD & EAD  
  - Cumulative default probability at Year 5 and Year 10  
- Perform stress testing:
  - Shock LGDs year-wise (capped at 100%) and recompute stress ECL.
  - Simulate rating downgrades in Year 10 and assess impact on ECL.
- Deliver insights in a research-style analyst report.

## Features
- Creative portfolio visualizations (rating mix, migrations, risk concentration).
- Automated PD & ECL computation using transition matrices.
- Multi-horizon cumulative default modeling.
- Scenario-based stress testing (LGD shocks & forced downgrades).
- Fully reproducible workflow (Python/Excel).

## Tech Stack
- Python (Pandas, NumPy, Matplotlib/Seaborn) / Excel
- Jupyter Notebook for analysis
- Structured report outputs


