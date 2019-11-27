# Titanic_EDA
**Exploratory Data Analytics on titanic dataset from kaggle competition and predicting the survivors.**

1. We have firstly filled all the NAN values of various columns by grouping with the relevant catagories.
2. We then identified relationships of several features with respect to one another.
3. Only **relevant features** are used for training and the redundancy is reduced by dropping those features.
4. **Random Forest model** is used for classification where **Stratified K-Fold** cross-validation technique is used and **Grid Search** is also used and all the parameters are tuned properly to get out best aacuracy.
5. We got an accuracy of approximately **82.49%** and was among the **top 10%**  in the leaderboard when submitted at that time.
