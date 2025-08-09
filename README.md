# Predicting the Success of Bank Telemarketing

## Project by: Shashi Kumar

## Project Overview
This project focuses on building a **Machine Learning Pipeline (MLP)** to accurately predict the **success of bank telemarketing campaigns**.  
Using customer and campaign attributes, we aim to forecast whether a client will subscribe to a bank term deposit (`yes` or `no`).  

The project is built as part of an **end-to-end Data Science workflow**, showcasing data preprocessing, feature engineering, model training, evaluation, and prediction.

---

## Dataset Description
The data is related with direct marketing campaigns of a banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

## Files:
- `train.csv` – Training dataset.
- `test.csv` – Test dataset.
- `sample_submission.csv` – a sample submission file in the correct format

## Input variables:
- `last contact date`: last contact date
- `age` (numeric)
- `job`: type of job
- `marital`: marital status (categorical: "married", "divorced", "single"; note: "divorced" means divorced or widowed)
- `education` (categorical: "unknown", "secondary", "primary", "tertiary")
- `default`: has credit in default? (binary: "yes", "no")
- `balance`: average yearly balance, in euros (numeric)
- `housing`: has housing loan? (binary: "yes", "no")
- `loan`: has a personal loan? (binary: "yes", "no")
- `contact`: contact communication type (categorical: "unknown", "telephone", "cellular")
- `duration`: last contact duration, in seconds (numeric)
- `campaign`: number of contacts performed during this campaign and for this client (numeric, includes last contact)
- `pdays`: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
- `previous`: number of contacts performed before this campaign and for this client (numeric)
- `poutcome`: outcome of the previous marketing campaign (categorical: "unknown", "other", "failure", "success")

## Output variable (desired target):
- `target`: has the client subscribed a term deposit? (binary: "yes","no")

---

## Tech Stack
- **Programming Language:** Python
- **Libraries & Frameworks:**
  - Data Handling: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`

---

## Project Workflow
1. **Data Loading & Exploration**  
   - Import datasets  
   - Explore structure, missing values, and distributions  

2. **Data Preprocessing**  
   - Handle missing values  
   - Encode categorical variables  
   - Scale numerical features  

3. **Model Development**  
   - Build and train multiple classification models (e.g., Logistic Regression, Random Forest, MLP)  
   - Evaluate using metrics like accuracy, precision, recall, and F1-score  

4. **Hyperparameter Tuning**  
   - Grid Search / Random Search for model optimization  

5. **Final Prediction & Submission**  
   - Generate predictions for the test set  
   - Save results in the correct format for submission  

---

## Visualizations
- Class balance plots  
- Correlation heatmaps  
- Feature importance rankings  

---

## Results
The final selected model demonstrated strong predictive performance, successfully identifying high-probability clients for subscription — helping optimize marketing resources.

---
