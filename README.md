# UK Flight Punctuality Analysis 2025 - Research Methods Assignment 
## Predicting Flight Delays Using Logistic Regression

## Description
This project analyses UK flight punctuality data published by the 
UK Civil Aviation Authority (CAA) for 2025. It builds a logistic regression model to predict whether a flight route will 
be chronically delayed. 

## Research Question
Can the operational characteristics of the UK flight route reliably predict whether that route will be chronically delayed, and what improvement in prediction accuracy is achieved by combining multiple operational features compared to a single historical predictor?

## Prerequisites
- Python 3.11
- Google Colab 
- See requirements.txt for all dependencies

## Installation
pip install -r requirements.txt

## Project Structure
- data/        — CAA 2025 Punctuality Statistics CSV file
- notebooks/   — Main analysis notebook 
- outputs/     — All generated plots 
- report/      — Final Word report 

## How to Run
1. Upload the CSV file to Google Colab or Jupyter
2. Run flight_punctuality_analysis.py

## Data Source
UK Civil Aviation Authority (CAA) — 2025 Annual Punctuality 
Statistics — Full Analysis
https://www.caa.co.uk/data-and-analysis/uk-aviation-market/flight-punctuality/

## Key Findings
- 54% of UK routes failed the IATA 15-minute punctuality threshold
- Univariate model accuracy: 56.2% (AUC: 0.624)
- Multivariate model accuracy: 86.4% (AUC: 0.937)
- Improvement: +30.2 percentage points

## Model Performance
| Metric    | Univariate | Multivariate |
|-----------|-----------|--------------|
| Accuracy  | 56.2%     | 86.4%        |
| Precision | 59.6%     | 90.7%        |
| Recall    | 62.4%     | 83.8%        |
| F1-Score  | 0.610     | 0.871        |
| AUC-ROC   | 0.624     | 0.937        |

## Libraries Used
- pandas — data loading and manipulation
- numpy — numerical operations
- matplotlib — visualisations
- scikit-learn — logistic regression and evaluation


## References
- UK Civil Aviation Authority (2025)
- Alshammari (2026)
- Chowdhury et al. (2026)
- Lu et al. (2021)
- Snell et al. (2026)
- Hatipoglu & Tosun (2024)
- Kafle & Zou (2016)



