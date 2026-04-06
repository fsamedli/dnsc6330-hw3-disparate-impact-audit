# dnsc6330-hw3-disparate-impact-audit
# DNSC 6330 - Individual Homework 3  
**Disparate Impact Audit**

## Purpose
This repository performs a complete disparate impact audit on the logistic regression model that predicts two-year recidivism (`two_year_recid`), exactly as required in Homework 3.

It includes:
- Computation of AIR, ME, and SMD for race and sex
- Intersectional analysis (race × sex) with worst-group AIR
- FPR and FNR by race, with statistical significance testing (two-proportion z-test)
- Publication-quality grouped bar chart of FPR and FNR by race (Caucasian as reference)
- 300-word compliance memo addressed to a hypothetical regulator

## Libraries Used
- pandas, numpy  
- scikit-learn (pipeline, preprocessing, logistic regression)  
- matplotlib, seaborn (visualization)  
- scipy (statistical testing)

## How to Reproduce
1. Clone the repository:  
   `git clone https://github.com/fsamedli/dnsc6330-hw3-disparate-impact-audit.git`
2. Install required packages:  
   `pip install pandas numpy scikit-learn matplotlib seaborn scipy`
3. Open `hw3_disparate_impact_audit.ipynb` and run all cells.

All outputs are fully reproducible.

## AI Assistance Statement
AI assistance (Grok) was used **solely** to draft and refine this README.md file to improve clarity and professionalism.  
The entire Python notebook (`hw3_disparate_impact_audit.ipynb`) — including data loading, preprocessing, model training, fairness metric calculations, statistical testing, visualizations, and the compliance memo — was implemented by the author. Only minor guidance was received on GitHub navigation and repository setup.

## Files
- `hw3_disparate_impact_audit.ipynb` ← main notebook  
- `README.md`
