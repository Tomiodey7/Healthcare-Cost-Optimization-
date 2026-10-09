# Healthcare Cost Optimization | 55K Patients

**Tools:** Python (Pandas)

## Problem
55,074 patients, $1.41B revenue, but Avg Length of Stay 15.5 days vs industry 4-6 days. Hospital cost variance $1K - $52K for same conditions.

## What I Did
- Cleaned 55.5K rows: fixed names, dates, removed 426 negative/low billing errors, standardized 500+ hospital variants into Hospital_Group
- Created LOS_days feature
- Found top cost drivers: Diabetes, Obesity, Arthritis = 73% of spend

## Key Insights (from screenshot)
<img width="814" height="254" alt="EDA-results" src="https://github.com/user-attachments/assets/b3604775-8c54-44a7-b719-fb97edcb91fa" />

## Files
- `healthcare_dataset_clean.csv` - cleaned
- `Healthcare dataset (1).ipynb` - full cleaning + EDA
## Data Preview(cleaned)
<img width="1349" height="351" alt="Data Preview" src="https://github.com/user-attachments/assets/6aa149ac-d35f-4778-8a3a-38aaec0f05c4" />
