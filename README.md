# Profit-Prediction
The target is to prepare an ML model which can predict the profit value of a company if the value of its R&D Spend, Administration Cost and Marketing

Link for the dataset: https://drive.google.com/file/d/1Z7RKmScBO7n9vcDIG3Xeo853Ics4QFaF/view

Also created a working web app for live prediction of profit if the user enters R&D spend, admin cost and marketing as well as can enter personal csv file to calculate the profit and also it shows the outliers and the most important feature.

STEP 1: Install python libraries: pip install flask pandas numpy scikit-learn matplotlib joblib 

STEP 2: Train the Model + Generate Feature Importance: python train_model.py

STEP 3: Generate Outlier Plot: python evaluation.py 

STEP 4:Run the Flask Web App: python app.py 

STEP 5:Running on http://127.0.0.1:5000
