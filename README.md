# shoppers-purchasing-intention:
The goal is to predict the purchasing intentions of online shoppers.

# Requirements
Python 3.8+ Jupyter Notebook - Kaggle Notebook is preferrable.

# Dataset
Movie Dataset : https://www.kaggle.com/datasets/imakash3011/online-shoppers-purchasing-intention-dataset


# How to Run The Notebook.
1. Login to Kaggle.com
2. Visit  https://www.kaggle.com/datasets/imakash3011/online-shoppers-purchasing-intention-dataset
3. Click on "New Notebook" Option Available on the top of the screen.
4. Download the ".ipynb" File attached in the current repository, select the right version
5. Upload On the New Notebook place by clicking on Import Notebook option.
6. Run The Notebook program

# Run the program in virtual envrionment python
1. Create virtual environment
2. Activate virtual environment
3. Install requirements.txt 
4. Run jupyter notebook and Open the .ipynb notebook file on the localhost:8888

# Key Data Insights
1. Weekend vs. Weekday Visits:
     *  Visualization: A pie chart was created to analyze the distribution of visits based on weekends and weekdays in relation to revenue generation.
     *  Insight: It was observed that website visits were significantly lower on weekends compared to weekdays. This indicates that user engagement and purchasing  i 
                  interest are higher during the weekdays.
2. Browser Usage and Revenue:
     * Visualization: Another pie chart was plotted to examine the relationship between different web browsers used by visitors and their revenue contribution.
     * Insight: The analysis highlighted which browsers were more commonly associated with higher revenue, providing insights into user preferences and potential 
                optimization for certain browsers.
3. Visitor Type and Revenue:

     * Visualization: A pie chart was also used to analyze the types of visitors (returning users, new users, and others) and their respective contributions to revenue.
     * Insight: The results showed that returning users constituted the largest segment, followed by new users, with "others" being the smallest segment. This suggests 
                that loyalty and repeated visits are crucial for revenue generation, while new user acquisition remains important.

4. Model Fitting and Evaluation:
      1.  Data Scaling and Model Tuning: The data was scaled to ensure uniformity and better model performance. Two models were tuned and fitted: Decision Tree and                                               Random Forest.
      2.  Model Performance:
             *  Random Forest: This model outperformed the Decision Tree in terms of both fitting and prediction accuracy. It was evaluated using key metrics such as 
                                 the classification report, accuracy score, and confusion matrix.
      3. Evaluation Metrics:
             Precision:  For False revenue (no purchase), the precision was high at 0.91.For True revenue (purchase made), the precision was 0.73.
             Recall: For False revenue, the recall was very high at 0.96, indicating that most non-purchase instances were correctly identified. For True                                     revenue, the recall was lower at 0.51, suggesting that the model missed a significant number of actual purchase instances.
5. To summarize the results above, based on the prediction results we can conclude that shoppers who do not intend to buy the product are correctly predicted not to buy 
    the product on the ABC online store web page as many as 2,049 shoppers. So that the class recall value is equal to 96% with the accuracy of the score is 89.37%. 
