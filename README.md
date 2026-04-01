Health Cost Prediction (Regression)


This project is based on predicting healthcare costs using a regression model in a Jupyter Notebook.
About
The notebook (fcc_predict_health_costs_with_regression.ipynb) contains the full workflow for predicting medical expenses using machine learning.
The dataset includes features like age, BMI, number of children, smoking status, and region. The goal is to predict the expenses value based on these inputs.


What I Did:

In this project, I followed these steps:
•	Loaded and explored the dataset
•	Cleaned the data and handled missing values
•	Converted categorical columns (sex, smoker, region) into numerical format
•	Split the data into training and testing sets (80/20)
•	Separated features and labels
•	Applied normalization to improve model performance
•	Built and trained a neural network using TensorFlow/Keras
•	Evaluated the model using Mean Absolute Error (MAE)


Model:


The model is a simple neural network with dense layers. Since this is a regression problem, the output layer has one neuron.
The model is trained using:
•	Optimizer: Adam
•	Loss Function: Mean Squared Error
•	Evaluation Metric: Mean Absolute Error (MAE)


Result:


The model achieves a Mean Absolute Error (MAE) close to the required threshold (below 3500), which means it can predict healthcare costs with reasonable accuracy.
Challenges
One important part of this project was handling categorical data properly. Without converting it into numerical form, the model would not work.
Another key step was normalization. After scaling the data, the model performance improved significantly.


How to Run:


1.	Open the notebook:
fcc_predict_health_costs_with_regression.ipynb
2.	Run all cells step by step in Jupyter Notebook or Google Colab


Conclusion:
This project helped me understand the importance of data preprocessing, feature engineering, and model tuning in regression problems. It also gave practical experience with TensorFlow and real-world datasets.

