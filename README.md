# Health Care Cost Prediction

This is the final project for Data 1030, Fall 2021 at Brown University.

We spend part of our money on health care every year, so I think it is necessary to collect some data to predict the annual expenses according to each person's own situation, and then purchase appropriate medical insurance or save enough money to deal with the possible expenses according to the conclusion.

This project attempts to create a regression model from the health condition of an individual to predict his or her annual health care cost. The dataset used for this project came from the Medical Cost Personal Datasets in Kaggle\cite{3}, which includes age, sex, bmi, children, smoker, region and charges. Through 6 features of 1338 individuals, I want to explore which factors are closely related to our target variable 'charges', and whether we can predict some person’s medical insurance expenditure once we obtain these factors. This will greatly help the insurance company price medical insurance. Furthermore, individuals will have the benefit of understanding the medical expenses he will pay as well.

This project uses Python 3.8.8 and packages as follow:

scikit-learn:                       0.24.1\
seaborn:                            0.11.1\
matplotlib:                         3.3.4\
pandas:                             1.2.4\
numpy:                              1.20.1\
xgboost:                            1.5.1\
shap:                               0.40.0
