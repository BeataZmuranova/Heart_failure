This notebook contains many interactive graphs, to see them, open it in Google Colab.

Context

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of five CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.
People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

This notebook contains exploratory data analysis, models: Logistic Regression, Random Forest Classifier, Gradient Boosting Classifier and feature importance. 

The best performing model based on Recall was Random Forest Classifier with the best score of 0.90. I chose Recall, because in this case we want to minimize type II errors(false negative).
