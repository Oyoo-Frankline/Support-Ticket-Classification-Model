# Support Ticket Classification & Prioritization

## Project Overview
This project explores machine learning techniques for classifying customer support tickets by ticket type and priority.

## Tools and Libraries
- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- Jupyter Notebook

## Models and Results
- **Ticket Type:** 17.41% accuracy
- **Ticket Priority — original model:** 25.21% accuracy
- **Ticket Priority — unigram and bigram model:** 25.74% accuracy

The models did not outperform their majority-class baselines. The results highlight the challenges of predicting labels from noisy or repetitive ticket text.

## Key Learning Outcomes
- Text preprocessing and exploration
- Converting text into numerical features using TF-IDF
- Training classification models
- Evaluating predictions using accuracy, precision, recall, and F1-score
- Comparing models against baseline performance

## Future Improvements
- Review data quality and label consistency
- Improve text cleaning
- Explore additional features and classification algorithms
