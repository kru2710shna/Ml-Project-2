# Fraud Detection with BigQuery ML

## Project Description

This project focuses on leveraging BigQuery ML, a powerful machine learning tool on Google Cloud, to analyze public financial transactions data for fraud detection. The dataset includes essential features such as transaction type, amount transferred, account IDs of origin and destination, new and old balances, and the relative time of the transaction. The target variable, `isfraud`, indicates whether a transaction is fraudulent.

### Objectives:

1. **Data Exploration:**
   - Load the financial transactions data into BigQuery.
   - Explore the dataset to understand its structure and characteristics.

2. **Feature Engineering:**
   - Create new features in BigQuery to enhance the model's predictive power.

3. **Unsupervised Anomaly Detection:**
   - Develop unsupervised machine learning models to identify anomalies in the data.

4. **Supervised Fraud Detection:**
   - Train supervised models, including logistic regression and boosted trees, for fraud detection.

5. **Model Evaluation:**
   - Evaluate and compare the performance of different models to select the most effective one.

6. **Champion Model Selection:**
   - Choose the best-performing model as the champion for fraud detection.

7. **Predictions on Test Data:**
   - Apply the selected model to predict the likelihood of fraud on a test dataset.

### Implementation Options:

- **BigQuery Interface:**
  - Utilize BigQuery ML for feature engineering, model development, evaluation, and prediction.

- **AI Platform Notebooks:**
  - Participants preferring notebooks can build models in AI Platform Notebooks using open-source libraries or BigQuery magic commands.

- **Google Cloud AutoML:**
  - Optionally, participants can explore Google Cloud AutoML for automated model training using state-of-the-art algorithms. This process takes approximately 2 hours, and initiation at the beginning of the lab is recommended.

### Note:
- Ensure access to the Kaggle dataset or create a Kaggle account for data retrieval.
- Participants have flexibility in choosing the development interface (BigQuery, AI Platform Notebooks) based on personal preferences.
- Consider exploring Google Cloud AutoML for automated model training.

### Instructions:
- Follow the step-by-step guide provided in the documentation to execute each phase of the project.
- Regularly check for important notes and attention phrases for optimal progress.

This project provides hands-on experience in financial fraud detection, showcasing the capabilities of BigQuery ML and offering options for participants with varied preferences in model development interfaces.
