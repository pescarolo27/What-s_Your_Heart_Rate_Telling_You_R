# What's Your Heart Rate Telling You? (R)

**The Background:** Millions of people develop some sort of heart disease every year, and heart disease is the biggest killer of both men and women in the United States and around the world. Statistical analysis has identified many risk factors associated with heart disease, such as age, blood pressure, total cholesterol, diabetes, hypertension, family history of heart disease, obesity, lack of physical exercise, and more.  
In this project, you will run statistical tests and models using the Cleveland heart disease dataset to assess one particular factor -- the maximum heart rate one can achieve during exercise and how it is associated with a higher likelihood of getting heart disease.

**Objectives:**
1) Manipulate the data and use statistical tests to see which predictors are related to heart disease as indicated by the `class` column. Adjust the `class` column to be binary where `0` indicates no heart disease and `1` represents the presence of heart disease. Save the three features with the highest significance to a list called `highly_significant`.
2) Fit a model using your highly significant features to predict the likelihood of heart disease, adjusting the results to be a binary outcome for probabilities greater than 0.5. Calculate and save the following model metrics: accuracy as a numeric variable `accuracy`, and the confusion matrix as `confusion`.
