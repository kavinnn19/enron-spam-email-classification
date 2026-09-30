
# Spam-Ham Email Classification using Machine Learning

## Project Description

This project uses Machine Learning to classify emails as Spam or Ham (legitimate).

The Enron Spam dataset is used to train and evaluate the model.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- Matplotlib
- Seaborn
- Joblib
- Google Colab

## Dataset

Enron Spam Dataset:
https://github.com/MWiechmann/enron_spam_data

The dataset contains email subjects, messages, and their Spam/Ham labels.

## Project Workflow

1. Load the dataset
2. Handle missing values
3. Combine email Subject and Message
4. Split the data into training and testing sets
5. Convert text into numerical features using TF-IDF
6. Train a Logistic Regression model
7. Predict Spam/Ham emails
8. Evaluate the model using performance metrics
9. Test the model with new emails
10. Save the trained model and TF-IDF vectorizer

## Model

Logistic Regression is used for classification.

TF-IDF (Term Frequency-Inverse Document Frequency) is used to convert email text into numerical features.

## Evaluation Results

- Accuracy: 99.01%
- Precision: 98.28%
- Recall: 99.80%
- F1 Score: 99.03%

## Testing

The trained model was tested with new emails and successfully classified example emails as Spam or Ham.

## Saved Files

- `spam_ham_model.pkl` - trained machine learning model
- `tfidf_vectorizer.pkl` - trained TF-IDF vectorizer
- `.ipynb` - Google Colab notebook containing the complete implementation

## How to Run

1. Download or clone this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Install the required Python libraries.
4. Run the notebook cells from top to bottom.
5. Enter a new email to test the Spam/Ham prediction.
