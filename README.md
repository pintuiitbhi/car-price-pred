# Predict Used Car Prices

### Installing

libraries and dependencies required to run this notebook is mentioned in "requirements.txt"

## Datasets

1. Submission.tsv : It contains the final prediction of test dataset.
2. cleaned_test_set.tsv : It contains the preprocessed test dataset.
3. actual_price_test.tsv : It contains the actual Price of test dataset
4. OLX_Car_Data_CSV.csv : Dataset downloaded from the kaggle website

## Split the Dataset
train and test data consists of 70% and 30%.

## Preprocessing
#### Feature Engineering
I have added one feature called "Damaged". If "KMs Driven" is more than 2000000 than it is too old else it is just old.


#### Handling Missing Values
I have used dummy variable to replace NaN for some features which seems important.

## Training
#### Model
I have used Linear Regression and RandomForestRegressor

## Evaluation
#### Metrics
Metrics used are R squared and Root mean squared error.

For Linear Regression R squrared score is about 80%

10-Fold cross validation is 80% and Training is score is 82%

## Conclusion
Best Model : RandomForestRegressor
R squared score is 85%.

10-Fold Cross Validation score is 85%.

Training score is 88%.

## Author
**Pintu Kumar**
**3rd Year 
IIT Bhilai Student**
