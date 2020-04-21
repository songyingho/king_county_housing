# Module 1: King County Housing

... Add visualizations

Executive Summary: Analyzing gathered data to create valuable information and recommendations for potential investors in the real estate market in Seattle.

Using the dataset given, we accomplished the following:
  1. Identified the 5 most influential features of a house that determines house prices in King County.
  2. Analyzed key figures of the target market's demand by conducting a cost benefit analysis on grade vs price.
  3. Identified the premium of renovating a house
  4. Provide recommendations to potential investors looking to develop real estate in King County.
  
Methodology: 
The project uses Python 3 and our expertise in real estate market to solve business problems
The project is documented with Jupyter Notebook
For data cleaning and analysis, we used pandas and numpy libraries
For data visualization, we used seaborn and matplotlib libraries
For linear regression, we used statsmodel running OLS regression models

High Level Overview:
Before starting the project, 3 questions were formulated to be answered by the conclusion of the project. Data was cleaned by extracting useful information from existing columns, removing duplicated rows, filling missing values, changing data types, checking and removing rows with incorrect values. Subsequently, we explored the data and created useful visualization for presentation. Finally, we tested several simple regression model and created a multi variable linear regression model to improve our existing model.

Results: 
 - Task 1: The task was solved by comparing the relationships between the variables and price by using a correlation matrix, then linear regression models are used to determine how well the features are used to explain house prices. The R-squared value improved from 0.49 to 0.6 with our multi variable linear regression model, there remains improvements to be made to the model.
- Task 2: The task was completed by analyzing the number of transactions and average price by property grade while evaluating the price range of properties most in demand in King County.
- Task 3: The premium was calculated by simple data extraction from the data given
- Task 4: Based on the insights obtained, recommendations are provided to potential investors to make an informed decision.

We hope this notebook has been helpful to provide clear information and valuable insights for the King County housing dataset. Thank you!
