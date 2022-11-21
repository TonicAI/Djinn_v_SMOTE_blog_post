# "Blog title"

Tonic's latest offering is a data synthesizer tailored specifically for data scientist's needs.  

## Meet Djinn

Using powerful AI generative models, Djinn takes a dataset from an application database - such as PostgreSQL or Oracle - a data warehouse - such as BigQuery or Snowflake - or simply from a CSV file, and creates rows of synthetic data that align with the trends in your data to allow you to build models with greater predictive power.

In this [blog post](link to blog) we use a dataset from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) to explore how Djinn helps improve classification model performance when working with imbalanced datasets. We compare the performance of Logistic Regression, XGBoost, and CatBoost models trained on datasets augmented using Djinn, SMOTE and SMOTE-NC.

Through addressing the biases associated with training models on imbalanced data by rebalancing the imbalanced class, we find that Djinn-augmented data outperforms the other augmentation methods for the CatBoost and XGBoost models. 

<hr>

## How to follow along

Head to [djinn.tonic.ai](https://djinn.tonic.ai/login?signup=true) to create your free account. Once you're logged in perform the following steps to get faking!
1. Create a workspace <br>
<br>
<p align="center">
  <img src="https://media.giphy.com/media/DVuaf1aPnR4skLht2l/giphy.gif">
</p>
<br>
2. Configure your source data (in this example we upload a CSV) <br>
<br>
<p align="center">
  <img src="https://media.giphy.com/media/cZbjDUabeeGG2OnDjR/giphy.gif">
</p>
<br>
3. Create a model with a SQL query - making sure to specify appropriate datatypes and column names <br>
<br>
<p align="center">
  <img src="https://media.giphy.com/media/EGJYgk7AiiB2IEa9dG/giphy.gif">
</p>
<br>
4. Set your model parameters and run your model <br>
<br>
<p align="center">
  <img src="https://media.giphy.com/media/fJHqnEKcVoJjWwcnHC/giphy.gif">
</p>
<br>
5. Check your synthesis report and copy your python snippet into your jupyter notebook<br>
<br>
<p align="center">
  <img src="https://media.giphy.com/media/iKUin0bBHqAr4UxxTQ/giphy.gif">
</p>
<br>

Recreate this experiment for yourself - head to [djinn.tonic.ai](https://djinn.tonic.ai/login?signup=true) to create your account and start your free trial!
