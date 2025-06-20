# Formation-Analysis-DML
Analyzes whether defensive formations like parking the bus offer real advantages in football. Uses 22k+ matches and a Double Machine Learning framework adapted for categorical treatments. Includes data from Sportmonks API, formation grouping, team strength features, and SHAP-based model interpretation.

Files:
- API_data.ipynb : Contains the necesary code to extract all the variables when it comes to a football fixture (events, line-ups, formations, statistics, general data, weather data, etc). 
- final_dataframe_construction.ipynb : Contains data cleaning and feature engineering steps, crucial for creating useful and valuable variables for the following DML model. 
- {goals,yellow_cards,red_cards,possession,corners,points}_matrix.ipnyb : Each one contains the DML process but using the defined statistic variable as target variable. It also displays the formations combinations beta estimators matrix (the ones which appear in the paper).
- goals_complementary_analysis.ipynb: Contains a feature importance study of the DML model that uses the goals difference as the target variable. 
