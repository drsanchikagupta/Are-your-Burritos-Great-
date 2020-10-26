# Are-your-Burritos-Great?
Using a dataset of [400+ burrito reviews](https://srcole.github.io/100burritos/), build a model that predicts whether a burrito is rated 'Great'?

Tasks-- Tutorial
 - Make a copy of this notebook to work on - you can download if you have a local Jupyter setup, or click File > Save a copy in Drive to copy and work on with Google Colab
 - Import the burrito csv file into a DataFrame. Your target will be the 'Great' column.
 - Conduct exploratory data analysis (EDA) to determine how you should clean the data for your pipeline.
 - Clean your data. (Note: You are not required to use all columns in your model, but justify your decisions based on your EDA.)
 - Do train/validate/test split. Train on reviews from 2016 & earlier. Validate on 2017. Test on 2018 & later.
 - Determine what the baseline accuracy is for a naïve classification model.
 - Create a scikit-learn pipeline with the following components:
  - A one hot encoder for categorical features.
  - A scaler.
  - A logistic regressor.
- Train your model using the training data.
- Create a visualization showing your model's coefficients.
- Get your model's validation accuracy (multiple times if you try multiple iterations).
- Get your model's test accuracy (one time, at the end).
