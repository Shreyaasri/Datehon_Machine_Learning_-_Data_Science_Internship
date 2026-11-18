# NLP Sentiment Classification on Customer Reviews (TF-IDF)

## Project Overview
This project uses Natural Language Processing (NLP) and machine learning to classify customer reviews into sentiment categories. Text data is cleaned and converted into numerical features using TF-IDF.

## Objectives
- Explore and clean customer review data.
- Preprocess text using Python.
- Extract text features using TF-IDF.
- Train Multinomial Naive Bayes and Logistic Regression models.
- Evaluate and compare model performance.
- Predict sentiment for custom customer reviews.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Regular Expressions (re)

## Project Workflow
1. Load and explore the dataset.
2. Handle missing values and duplicate records.
3. Clean and preprocess review text.
4. Split the dataset into training and testing sets.
5. Apply TF-IDF vectorization.
6. Train Multinomial Naive Bayes and Logistic Regression.
7. Evaluate model performance using accuracy, precision, recall, and F1-score.
8. Compare model results and predict sentiment for new reviews.

## Dataset
The dataset file is `sentiment_reviews.csv`.

It contains customer review text and corresponding sentiment labels. The current dataset contains only 10 reviews, so the evaluation results are preliminary.

## Models
- **Multinomial Naive Bayes:** A probabilistic classifier commonly used for text classification.
- **Logistic Regression:** A supervised machine learning algorithm used for classification.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Project Files
- `sentiment_classification.ipynb` — Notebook containing the complete workflow.
- `sentiment_reviews.csv` — Customer reviews dataset.
- `README.md` — Project documentation.

## Limitations
The dataset contains only 10 reviews. Therefore, the evaluation scores may be unstable and should not be treated as evidence of real-world model performance. A larger and more representative dataset is required.

## Future Improvements
- Use a larger customer review dataset.
- Apply cross-validation and hyperparameter tuning.
- Build an interactive web application.
- Evaluate performance on unseen real-world reviews.

## Author
Shreya Kumari
