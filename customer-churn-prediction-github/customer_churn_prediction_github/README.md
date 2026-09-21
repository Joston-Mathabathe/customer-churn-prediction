# Customer Churn Prediction & Retention Analytics

An end-to-end machine-learning portfolio project by **Joston Mathabathe**, combining a **Business Management** perspective with postgraduate **Data Science** skills.

## Business question
Which customers are more likely to churn, what characteristics are associated with higher churn risk, and how could a business use these insights to prioritise retention activity?

## Capabilities demonstrated

### Business Management
- Business problem framing
- Customer and segment analysis
- KPI design
- Risk and retention thinking
- Business recommendations
- Stakeholder-oriented communication
- Distinguishing association from causation

### Data Science
- Python, Pandas and NumPy
- Data cleaning and EDA
- Feature engineering
- One-hot encoding and scaling
- Logistic Regression and Random Forest
- Train/test splitting with stratification
- Precision, recall, F1 and ROC-AUC
- Confusion matrices and ROC curves
- Model interpretation
- Churn-risk segmentation

## Workflow
Business problem → Data acquisition → Data quality → EDA → Feature engineering → Preprocessing → Classification → Evaluation → Risk segmentation → Retention recommendations

## Dataset
IBM's public **Telco Customer Churn** sample dataset. IBM describes it as data for a fictional telecommunications company, with `Churn` indicating whether a customer departed within the last month.

The raw CSV is **not committed**. The notebook downloads it automatically from IBM's archived public GitHub repository.

## How to run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/customer_churn_prediction.ipynb
```
The notebook can also be opened in Google Colab.

## Evaluation
The project reports accuracy, precision, recall, F1-score and ROC-AUC. Recall and precision receive particular attention because a retention team has limited resources and missing genuine churners can represent missed opportunities.

## Business application
The model can support a retention prioritisation workflow using risk segments, customer value, campaign cost and business rules. Predictions should support decisions rather than be treated as certainty.

## Limitations
This is a portfolio/educational project using IBM sample data. It is a cross-sectional snapshot and does not provide monthly customer histories. It should not be presented as proof of future-month forecasting or causal evidence that a retention action causes customers to stay.

For production, I would add time-based validation, probability calibration, model monitoring, fairness checks, cost-sensitive threshold optimisation and controlled experiments.

## Repository structure
```text
customer-churn-prediction/
├── notebooks/
│   └── customer_churn_prediction.ipynb
├── data/
│   └── README.md
├── docs/
│   └── BUSINESS_SUMMARY.md
├── src/
│   └── README.md
├── .gitignore
├── requirements.txt
└── README.md
```

## Author
**Joston Mathabathe**  
BCom Business Management Graduate — University of Pretoria  
Postgraduate Diploma in Data Science — University of the Witwatersrand

`Python` `Pandas` `NumPy` `Scikit-learn` `Machine Learning` `Data Analytics` `Business Analytics` `Customer Analytics`
