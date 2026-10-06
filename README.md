# AI-Based Spam Email Detection

## Project Description

This project uses Machine Learning to detect whether a text message is Spam or Not Spam.

## Objective

The main objective is to automatically classify messages into:

* Spam
* Not Spam (Ham)

## Technologies Used

* Python
* Google Colab
* Pandas
* Scikit-learn
* TF-IDF
* Multinomial Naive Bayes
* Matplotlib

## Dataset

The project uses the SMS Spam Collection dataset.

The dataset contains messages labelled as `spam` or `ham`.

## Methodology

1. Load the dataset
2. Analyze the data
3. Split the data into training and testing sets
4. Convert text into numerical features using TF-IDF
5. Train the Multinomial Naive Bayes model
6. Test the model
7. Calculate accuracy and other performance measures
8. Predict whether new messages are spam or not spam

## Model

The project uses the Multinomial Naive Bayes algorithm for classification.

## Results

The model was evaluated using accuracy, precision, recall, F1-score and a confusion matrix.

The final accuracy is based on the actual result obtained during testing.

## Future Work

* Create a user-friendly interface
* Test with larger email datasets
* Try other machine-learning algorithms
* Improve the model's performance
* Deploy the application

## Project Files

* `AI_Spam_Email_Detection.ipynb` – Python/Jupyter Notebook
* `README.md` – Project information
* `screenshots/` – Project output screenshots

