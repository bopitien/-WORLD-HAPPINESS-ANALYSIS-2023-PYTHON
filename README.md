# -WORLD-HAPPINESS-ANALYSIS-2023-PYTHON

Each year, the Global Public Sentiment Survey assesses popular opinions on a range of subjects, from governance to socio-economic matters, in around 150 nations worldwide. One key output of this exercise is the Annual World Well-Being Assessment. While happiness or well-being might initially appear as intangible or emotional metrics, they have gained considerable attention from governments as meaningful measures of national success. These happiness ratings offer an average national response to life-satisfaction queries and serve as a crucial reminder that a nation's success isn't solely tied to its economic performance. Instead, well-being metrics provide a nuanced view, emphasizing the role of social factors in shaping contentment. They offer invaluable insights for shaping effective public policies and underscore the importance of focusing on qualitative aspects of life, rather than just the quantitative

## About Data

The dataset utilized in this study contains comprehensive metrics to evaluate the happiness level across different countries. Key variables include the "Happiness Score," "Logged GDP per capita," "Social support," "Healthy life expectancy," "Freedom to make life choices," "Generosity," and "Perceptions of corruption." This rich dataset provides a unique opportunity to explore the complex dynamics that contribute to national happiness levels.

## Data Source
The dataset for this study was sourced from Kaggle, specifically from the World Happiness Report 2023 provided by user Joe Beach Capital. The dataset is available at Kaggle World Happiness Report 2023. This dataset is an invaluable resource that includes a variety of metrics related to happiness, economy, social support, and health among others, allowing for a robust analysis and modeling.


## Objectives

* Exploratory Data Analysis (EDA): To understand the distribution, trends, and correlations among variables.
* Correlation Analysis: To identify the relationship between happiness and various factors like GDP, social support, and freedom.
* Comparative Analysis: To compare the top 10 happiest countries with the bottom 10, focusing on their key characteristics.
* Predictive Modeling: To develop a machine learning model that can predict a country's happiness score based on the other variables in the dataset.


## Summary of Insights:
### Data Source and Objective:

i utilized the World Happiness Report dataset from Kaggle to understand the factors affecting happiness across various countries.
Our objective was to create a predictive model using supervised machine learning techniques to predict the Happiness Score based on six independent variables: Logged GDP per capita, Social support, Healthy life expectancy, Freedom to make life choices, Generosity, and Perceptions of corruption.

#### Exploratory Data Analysis (EDA):
Preliminary data analysis revealed notable differences in Happiness Scores across continents, with Europe and Oceania ranking highest and Africa ranking the lowest.

#### Model Building and Evaluation:
After normalizing the data using the Z-Score method, we employed a Linear Regression model.
The model showed an R-squared value of approximately 0.81, indicating that about 81% of the data fits the regression model.
The Mean Squared Error was found to be 0.184, which suggests a reasonable level of error given the scale of our Happiness Scores.

#### Variable Significance:
Social support and GDP per capita were the most significant factors affecting happiness. Interestingly, Perceptions of corruption had a negative impact on happiness.

#### Residual Analysis:
Residual plots did not show any particular pattern, indicating that the model's assumptions are not violated significantly.

#### Recommendations:
* Given the strong positive influence of GDP and Social support on Happiness Scores, policy makers should focus on economic policies that enhance GDP and social policies that improve the sense of community and belonging among citizens.

#### Future Research:
* It might be beneficial to include more variables like education, employment rate, etc., to improve the model's predictive power.
* While the current dataset is robust, more recent data can be included for up-to-date insights. It would also be interesting to see how these variables are influenced by global phenomena like pandemics or economic crises.

#### Utility of the Model:
This model can serve as a preliminary tool for various organizations or governments to understand the factors affecting happiness and take corrective actions accordingly.
By following these insights and recommendations, we can aim for a more comprehensive understanding and promotion of happiness on a global scale.
