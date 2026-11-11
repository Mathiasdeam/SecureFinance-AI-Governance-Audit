# SecureFinance Africa: AI Governance & Fairness Audit

## Overview
This repository contains the technical artifacts and algorithmic fairness assessment for the AI-driven credit scoring and identity verification platform of SecureFinance Africa. The project demonstrates compliance with international AI governance frameworks (NIST AI RMF, EU AI Act) and technical mitigation of algorithmic bias.

## Repository Contents
* `AI_Governance_Audit_Report.pdf`: The complete final assessment report covering Hard/Soft Law compliance and risk management.
* `fairness_audit.py`: Python script containing the reproducible technical audit (Random Forest model, bias metrics, and mitigation).
* `synthetic_credit_dataset.csv`: A generated dataset of 1,000 synthetic client profiles.
* `fairness_audit_results.png`: Visual evidence of the fairness evaluation (Disparate Impact Ratio) and Explainable AI (XAI) feature importance.

## How to Run the Audit
1. Ensure Python 3.x is installed.
2. Install the required libraries: `pip install pandas numpy scikit-learn matplotlib`
3. Execute the script: `python fairness_audit.py`