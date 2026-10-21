# Credit Risk Analysis Using Machine Learning

## About the Project
This project uses machine learning to predict whether a person may have difficulty repaying a loan. It uses applicant details such as age, income, work experience, and home ownership to make predictions.

## Project Goals
- Understand and analyze the dataset.
- Clean and prepare the data.
- Build a machine learning model.
- Predict loan risk.
- Check how well the model performs.
- Visualize the results using graphs.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Dataset
The dataset contains information about loan applicants, including:
- Age and income
- Work experience
- Marital status
- Home and car ownership
- Job and housing details

The target column is `Risk_Flag`, which is used to predict loan risk.

## Steps Followed
1. Loaded and explored the dataset.
2. Selected the features needed for prediction.
3. Split the data into training and testing sets.
4. Prepared numerical and categorical data.
5. Trained a Random Forest model.
6. Made predictions using the test data.
7. Evaluated the model using different metrics.
8. Created graphs to understand the results and important features.

## Model Evaluation
The model is evaluated using:
- Precision, recall, and F1-score
- Confusion matrix
- ROC curve and ROC-AUC score
- Feature importance graph

## How to Run the Project
1. Download or clone this repository.
2. Install the required libraries:

   `pip install pandas numpy scikit-learn matplotlib joblib jupyter`

3. Keep the dataset in the correct folder.
4. Open the Jupyter Notebook.
5. Run the code cells one by one.

## Future Improvements
- Try other machine learning models.
- Improve prediction results.
- Add SHAP to better understand the predictions.
- Test different ways to handle imbalanced data.



## Author
Rachana Shivarkar
