# SC1015-Heart Disease
SC1015 Project

## About
This is the repo for the SC1015 mini-project. The aim of the this project is to predict the presence of heart disease/cardiovascular disease with the dataset from [UCI Machine Learning Repository.](https://archive.ics.uci.edu/ml/datasets/Heart+Disease "UCI ML")

## Contribution
@ - Neoh Kai Xiang
@wph12 - Weng Pei He
@fortuneblycat - Tan Ding Jiang

## Models Used
1. Decision Tree
2. Random Forest
3. Logistic Regression

## Conclusion
1. Heart Disease can be predicted with a reasonable degree of accuracy using the ML models
2. Random Forest gives the best performance with the dataset
3. Other important variables to consider are exercise-related: presence of exercise-induced angina, exercise-induced ST depression and ST Slope during peak exercise. As such, exercise tests can be very useful in detection of heart disease in patients.
4. Men are more prone to heart disease than Women
5. Asymptomatic chest pain in predicting heart disease: This could be attributed to the presence of silent myocardial infarctions, where patients might show atypical symptoms like indigestion, flu or a strained chest muscle, rather than the normal symptoms of heart attack, which usually involve sharp anginal pain. However, having these silent heart attacks are no less deadly, and still involve blockage of blood flow to the heart and possible damage to the heart muscles.

## Lessons Learnt
* Trade-offs when encountering missing values: deletion vs imputation
* Concept of imputation and the methods to carry it out
* Concept of over/undersampling
* Refactoring imbalanced categorical data 
* RandomForest Classifier
* Hyperparameter tuning with gridsearchCV
* Logistic Regression
* Google Colaboratory (which is not very great, will stick to Git in the future)

## References
Images
* https://litfl.com/wp-content/uploads/2018/10/ST-segment-depression-upsloping-downsloping-horizontal.png
* https://c8.alamy.com/comp/HNFH7G/ecg-of-non-st-elevation-myocardial-infarction-nstemi-and-detail-of-HNFH7G.jpg

Readings
* [Constanzo Physiology](https://www.elsevier.com/books/costanzo-physiology/costanzo/978-0-323-79333-9)
* https://towardsdatascience.com/how-to-handle-missing-data-8646b18db0d4
* https://towardsdatascience.com/an-extensive-guide-to-exploratory-data-analysis-ddd99a03199e
* https://towardsdatascience.com/all-about-missing-data-handling-b94b8b5d2184
* https://www.analyticsvidhya.com/blog/2021/10/guide-to-deal-with-missing-values/
* https://www.analyticsvidhya.com/blog/2021/10/handling-missing-value/
* https://quantifyinghealth.com/interpret-logistic-regression-coefficients/
* https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1123032/
* https://neptune.ai/blog/evaluation-metrics-binary-classification
* https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5543767/
* https://datahacker.rs/005-pytorch-logistic-regression-in-pytorch/
* https://quantifyinghealth.com/standardized-vs-unstandardized-regression-coefficients/
* https://datahacker.rs/005-pytorch-logistic-regression-in-pytorch/

