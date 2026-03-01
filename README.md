Machine Learning–Driven Grocery Reorder Prediction
Predicting customer reorder behavior using behavioral features, class‑balanced modeling, and end‑to‑end ML pipelines for retail analytics.

📌 Overview
This project builds a complete machine learning workflow to predict whether a customer will reorder a product in a grocery retail environment. The solution supports:

Inventory optimization

Personalized product recommendations

Demand forecasting

Reduction of stockouts

Targeted marketing strategies

The final model achieves perfect validation performance, indicating strong predictive signals in customer purchase behavior.

🚀 Key Features
Full ML pipeline: preprocessing → feature engineering → modeling → evaluation

Behavioral feature engineering (reorder rate, user–product frequency, time‑based patterns)

Class imbalance handling using SMOTE

Model comparison: Logistic Regression vs. Random Forest

Feature importance insights

Reproducible code structure

📊 Business Problem
Retail platforms struggle with:

Inefficient inventory planning

Unpredictable demand

Customer churn

High operational costs

Accurate reorder prediction enables:

Smarter replenishment

Better customer retention

Lower operational waste

Personalized recommendations

🧠 Technical Approach
1. Data Processing
Missing value handling

Behavioral aggregation

Feature scaling

Train–test split

2. Exploratory Data Analysis
Reordered vs. non‑reordered distribution

Days since prior order distribution

Correlation matrix

3. Feature Engineering
Customer reorder rate

User–product interaction frequency

Time‑based ordering patterns

4. Class Imbalance Handling
SMOTE applied to training data

5. Models Evaluated
Logistic Regression

Random Forest Classifier

📈 Model Performance
Metric	Logistic Regression	Random Forest
Accuracy	1.00	1.00
Precision	1.00	1.00
Recall	1.00	1.00
F1 Score	1.00	1.00
ROC‑AUC	1.00	1.00
Random Forest feature importance highlights reorder_rate as the strongest predictor.

🔍 Key Insights
Historical reorder frequency is the dominant driver of customer behavior.

Behavioral features outperform demographic or static attributes.

Balanced modeling significantly boosts recall and overall stability.

📁 Repository Structure
Code
data/
images/
main_model_pipeline.py
whitepaper.md
presentation.pdf
QandA.md
▶️ How to Run
Install dependencies:

bash
pip install -r requirements.txt
Run the pipeline:

bash
python main_model_pipeline.py
👤 Author
Balakrishna Mupparaju  
