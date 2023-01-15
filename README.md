# Digit-Recognizer
kaggle competition : https://www.kaggle.com/competitions/digit-recognizer/data

this is my jupyter nootbook to craet model to Recognize Digit.

my steps
1. load csv file from this competition.
2. normalize value by using /255.0.
3. reshape data into (-1,28,28,1) for CNN model.
4. split training data and validation data.
5. create CNN model.
6. train model
7. evaluate and predict
8. create csv file to submission
