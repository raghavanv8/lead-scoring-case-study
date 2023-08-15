# Lead Scoring Case Study

Lead Scoring Case Study depicts the analysis of leads data and predict whether leads would convert or not. 

## Steps involved

1.	Importing the Data 
2.	Inspecting the dataframe
3.	Data Preparation
    a.	Exploratory Data Analysis
        i.	Univariate analysis
        ii.	Bivariate analysis
    b.	Dummy Variables for Categorical Variables
    c.	Train – Test Split
4.	Model Building
    Build a logistic regression model and use RFE with 'n' variables for feature selection
    Assess the models using statsmodels.
    Predict on train data set. 
5.	Model Evaluation:
    Create confusion matrix using metrics. Check for the overall Accuracy, Sensitivity, Specificity.
    Previously, we chose a random cutoff at some point "ABC". To find the optimum value, we are plotting ROC Curve.
    Call the ROC function. Let's create columns with different probability cutoffs. Now let's calculate accuracy sensitivity and specificity for various probability cutoffs. Let's plot accuracy sensitivity and specificity for various probabilities.
    From the graph, we can see that the optimum cutoff value is "DEF".
    When predicting with cutoff as y, we can observe that accuracy, sensitivity and specificity changes. 
    Predict on test dataset.
    Scale numeric values. Substitute all the columns in the final train model. Make prediction using cut off "DEF".
    Check for the overall Accuracy, Sensitivity, Specificity.
    Next, we need to calculate Precision and Recall. We will find optimal point for Precisiona and Recall at "KLM".
    while making prediction using cut off "KLM", we observe that Precision and Recall changes.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project belongs to Raghunath, Raghavan and Sachin.

https://github.com/raghavanv8

https://github.com/sachin1559095