 The objective of this assignment is to evaluate your understanding of regression techniques in supervised learning by applying them to a real-world dataset. 
 Use the California Housing dataset available in the sklearn library. This dataset contains information about various features of houses in California and their respective median prices.

 Key Components to be Fulfilled:
1.	Loading and Preprocessing:

○	Load the California Housing dataset using the fetch_california_housing function from sklearn.
○	Convert the dataset into a pandas DataFrame for easier handling.
○	Handle missing values (if any) and perform necessary feature scaling (e.g., standardization).
○	Explain the preprocessing steps you performed and justify why they are necessary for this dataset.

2.	Regression Algorithm Implementation (5 marks):
 Implement the following regression algorithms:

○	Linear Regression
○	Decision Tree Regressor
○	Random Forest Regressor
○	Gradient Boosting Regressor
○	Support Vector Regressor (SVR)
 
 For each algorithm:
○	Provide a brief explanation of how it works.
○	Explain why it might be suitable for this dataset.

3.	Model Evaluation and Comparison (2 marks):
○	Evaluate the performance of each algorithm using the following metrics:
■	Mean Squared Error (MSE)
■	Mean Absolute Error (MAE)
■	R-squared Score (R²)

○	Compare the results of all models and identify:
■	The best-performing algorithm with justification.
■	The worst-performing algorithm with reasoning.

FINAL CONCLUSION

THE BEST MODEL  : "RANDOM FOREST TREE REGRESSION" WITH PREDICTION ACCURACY IS 78%
THE WORST MODEL : "DECISION TREE REGRESSION" WITH PREDICTION ACCURACY LOWEST OF ALL - ONLY 57%

	                                               MSE       MAE	  R2 Score
K-Nearest Neighbors (KNN) REGRESSION	        0.387299	0.441927	0.660450
LINEAR REGRESSION	                            0.387299	0.441927	0.660450
DECISION TREE REGRESSION	                    0.482077	0.443368	0.577357
RANDOM FOREST TREE REGRESSION	                0.250842	0.329281	0.780084
GRADIENT BOOSTING REGRESSION	                0.283940	0.372786	0.751066
SUPPORT VECTOR MACHINE REGRESSION	            0.283940	0.372786	0.751066

*** PLEASE SEE COMMENTS FOR EACH STEPS ON THE CODE FOR MORE CLARIFICATION ON EACH AND EVERY STEPS TAKEN FROM DATA PREPROCESSING TILL MODEL CREATION
