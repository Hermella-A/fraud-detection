# Fraud Detection for Adey Innovations Inc.

## Project Overview
This project builds fraud detection models for two transaction streams: e-commerce and bank credit cards.

## Repository Structure 
├── .github/workflows/ci.yml # CI/CD pipeline
├── data/ # Raw and processed data (ignored by Git)
├── notebooks/ # Jupyter notebooks for EDA, feature engineering, modeling
├── src/ # Python modules
├── tests/ # Unit tests
├── models/ # Saved model artifacts (ignored)
├── requirements.txt
└── README.md
## Setup
1. Clone the repository
2. Create virtual environment: `python -m venv venv`
3. Activate: `venv\Scripts\activate` (Windows)
4. Install dependencies: `pip install -r requirements.txt`
5. Place datasets in `data/raw/`
