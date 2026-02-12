# Space-X-Launches-Analysis
## Exploratory data analysis, using the Jupyter Notebook environment, where the different steps of the data analysis process are followed.
------
1. We started defining the problem: Perform a thorough analysis on the data available in the API, studying the percetnage of successful launches under different conditions and seeking to establish a model for prediction of first-stage-recovery.

2. The data from the SpaceX Public API were collected, and after that, the Wikipedia page related to the list of launches performed by SpaceX was also scraped.  

3.  An Exploratory Data Analysis (EDA) was performed, using SQL to perform different requests in order to discover insights from the data.

4.  Using mainly Seaborn and Pandas, different graphs and charts were designed to visually study the different variables available in our data. Several scatter plots were performed to study correlation between different variables.

5.  Data were represented as interactive visualization using Folium, focusing on the success rate of launches depending on their location (different space force base in the US).

6.  Several Machine Learning models were trained with the available data, splitting it into training and testing data. Models were trained with training set, refining the values of the hyperparameters with GridSearchCV, and their corresponding test scores were obtained using the testing subset.
    Finally, their performance as otucome predictors was visually evaluated generating the corresponding confusion matrix for each model.

## We concluded that the trained models had an acceptable accuracy for outcome prediction (test score aroung 0.83, except for Decission Tree Model), yet they presented problems with false positive detection
