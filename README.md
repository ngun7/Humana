# Humana-Analytics-Case-Competition
Humana-Mays Healthcare Analytics Case Competition 2020 

# Business Case Description #
Social determinants of health are the conditions in the environments in which people live, learn, work, play, worship and age that affect a wide range of
health, functioning and quality-of-life outcomes and risks. Transportation challenges is one of these determinants.

• Using the data provided and potentially supplementing with public data, create a model to predict which Medicare members are most likely struggling with 
Transportation Challenges. <br/>
• Propose solutions for overcoming these barrier to accessing care and achieving their best health. 

# Data Included:
• Medical claims features <br/>
• Pharmacy claims features <br/>
• Lab claims features <br/>
• Demographic / Consumer data <br/>
• Credit data features <br/>
• Clinical Condition related features <br/>
• CMS Member Data elements <br/>
• Other features <br/>


2020_Competition_Training.csv		= Data to be used for analysis & model development
2020_Competition_Holdout.csv		= Holdout data to be scored with final model and results 
2020_Competition_Data_Documentation	= File Statistics, File Layout, descritions of attributes for each event type 

Highly imbalanced dataset having 69,572 observations with 826 columns. 
'transportation_issues' : 14.66% of total observations. 

As part of EDA, applied variance threshold, percebntage of missing values threshold, single unique value percent, one-hot encoding of categorical variables and then cardinality aggregation and correlation analysis. After obtaining final dataframe, performed PCA to reduce dimensionality without compromsing for capturing maximum variance. And, then tried various sampling techniques to address class imbalance issue and then finally implemented different machine learning models and tuned hyperparameters accordingly.
