Red wine data set used in this report contains 4898 observations with 11 features qualifing the chemical properties of different variants of Portuguese “Vinho Verde” wine from 2009 source that are measured by physicochemical test. Here, Each property plays important role in defining the wine taste and quality.The quality varaible is based on sensory data contains median of the ratings given by at least 3 experts from 0(very poor) to 10(very excellent).
The dataset is available on the UCI machine learning repository (https://archive.ics.uci.edu/ml/datasets/wine+quality). 

Input variables (based on physicochemical tests):
1 - fixed acidity (tartaric acid - g / dm^3)
2 - volatile acidity (acetic acid - g / dm^3)
3 - citric acid (g / dm^3)
4 - residual sugar (g / dm^3)
5 - chlorides (sodium chloride - g / dm^3
6 - free sulfur dioxide (mg / dm^3)
7 - total sulfur dioxide (mg / dm^3)
8 - density (g / cm^3)
9 - pH
10 - sulphates (potassium sulphate - g / dm3)
11 - alcohol (% by volume)
Output variable (based on sensory data):
12 - quality (score between 0 and 10)

I’ll analyze and explore the Red Wine data set to understand and find the factors that are resposible for determining the quality of Wine.I’ll start by visualizing and understanding each variable, then I find the correlation between quality and other variables.Lastly, I’ll create Linear Regression model to predict the quality.
