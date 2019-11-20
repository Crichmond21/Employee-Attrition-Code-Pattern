# Employee-Attrition-Code-Pattern
This is a prject for COMP - 3800 Impact of AI on Society at Wentworth Institute of technology, taught by Professor Armen Pischdotchian

In class we were assigned to use IBM's Auto AI tool to try to correctly classify the attrition of an employee based on several features such as salary, commute times, role, years with manager, etc. The ROC AUC score of the model trained with Auto AI seemed low at around 70% to me so I thought I would try and see if I could make a model that would perform better than IBM's Auto AI on this dataset before the end of the class.

### The Model
I wanted to use the same model that Auto AI used so I trained a logistic regression model to classify the data. I briefly experimented with a Random Forest Classifier as well but the results were not as promising as I wished they would be, so I stuck with logistic regression. I used a One Hot Encoder on all of the features to create a larger feature space and also did some resampling of the data to remove bias. At the end of my brief data science project I create a model with a slightly better ROC AUC score of around 73% but with more feature engineering I am confident that this score could be beaten again.  

### To Run
To run this code
1. Clone this repository
2. pip install numpy pandas sklearn
3. Run the jupyter notebook with the CSV file in the same directory
