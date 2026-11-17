# Financial Inclusion Predictor (XGBoost)

Predicts whether an individual in East Africa is likely to have a bank account, using an XGBoost classifier trained on FinScope survey data (2016 and 2018), and served as a Streamlit app.

## Run it

```bash
pip install -r requirements.txt streamlit
streamlit run conchitaapplast.py
```

Fill in the form (country, location, demographics, household details) to get the predicted financial-inclusion status.

## Stack

Python · pandas · scikit-learn · XGBoost · Streamlit
