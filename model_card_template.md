# Model Card

For additional information see the Model Card paper: https://arxiv.org/pdf/1810.03993.pdf

## Model Details
The model used is a RandomForestClassifier.
Version 1.0
2025-08-29

## Intended Use
This model is intended for predictive tasks. It was specifically designed to categorize an individual's income as either above or below $50K based on features such as age, occupation, marital status, and education level.
## Training Data
The model was trained with the CEnsus Income Dataset from the UCI Irvine Machine Learning Repository. Data link: https://archive.ics.uci.edu/ml/datasets/census+income
## Evaluation Data
The model was evaluated using a test set that contains 20% of the original dataset. The test set was randomly split from the original data. 
## Metrics
_Please include the metrics used and your model's performance on those metrics._
Performance of the model was evaluated using:
Precision: 0.7419
Recall: 0.6384
and F1 Score: 0.6863
## Ethical Considerations
The model is trained on census data, which is historical data, so it might not accurately represent current trends.
## Caveats and Recommendations
It's based on historical census data, so it may not accurately reflect current trends. Further improvements to the model could be made. 