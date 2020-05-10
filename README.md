# Wine Variety Prediction

# Description

This model is an implementation of NLP for wine variety prediction using the reviews given by various users.

# Natural Language Processing 

Natural Language Processing (aka NLP) is a field of AI that focuses on the ability of machines to comprehend languages and interpret messages.

# Data

1.The training set consists of 82657 obseravtions and 12 variables.

2.The test set consists of 20665 observations and 11 variables. (variety to be predicted)

3.The newtest set consists of the 20665 observations and 12 variables with the predicted coloumn.

4.The Data Description is as follows:

    •user_name - user_name of the reviewer

    •country -The country that the wine is from.

    •review_title - The title of the wine review, which often contains the vintage.

    •review_description - A verbose review of the wine.

    •designation - The vineyard within the winery where the grapes that made the wine are from.

    •points - ratings given by the user. The ratings are between 0 -100.

    •price - The cost for a bottle of the wine.

    •province - The province or state that the wine is from.

    •region_1 - The wine-growing area in a province or state.

    •region_2 - Specific regions within a wine-growing area, but this value can sometimes be blank.

    •winery - The winery that made the wine.

    •variety - The type of grapes used to make the wine. 

# Model

1.Models Used and accuracy in train: 1)Decision Tree: 0.5641785627873216
                                     2)Logistic Regression: 0.6847326397290104
                                     3)Support Vector Machine (Linear): 0.8487382224619010

2.Features extracted: review_description

3.Visualization of data and top 5 actionable Insights from the Data: EDA.ipynb

# Summary

Support Vector Machine (Linear) model outperforms the other models. Hence, SVM model is used on the test data and the variety of wines are predicted. This data is saved as the newtest.csv file.
