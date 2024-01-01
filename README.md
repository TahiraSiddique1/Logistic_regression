# Logistic_Regression
The code begins by installing the pandas library and reading a CSV file named 'banking.csv' into a DataFrame. There's an attempt to display the DataFrame using print(new_df.to_string()), but the output is cut off due to an exceeded IOPub data rate limit.

Following this, various bar plots are generated using matplotlib to visualize the distribution of the target variable 'y' across different features like job, marital status, loan status, and poutcome. These visualizations offer insights into how different factors may influence the target variable.

The code then creates dummy variables for categorical columns using the pd.get_dummies function. This is a common preprocessing step in machine learning to convert categorical variables into a format suitable for model training.

Next, the code splits the data into training and testing sets and performs a logistic regression analysis to predict the target variable 'y' based on the age feature. The accuracy of the logistic regression model is printed, indicating a model accuracy of 81%.

Finally, a correlation matrix is calculated for all numerical features in the dataset, and a heatmap is generated using seaborn to visually represent the correlations between these features. This step helps in understanding the relationships between different numerical variables.

In summary, the code involves data cleaning, exploratory data analysis through visualizations, preprocessing using dummy variables, and machine learning modeling with logistic regression. Additionally, it explores correlations between numerical features in the dataset.
