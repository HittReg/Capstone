Data Understanding and Feature Creation:

The Calendar table contains a large number of rows indicating frequent updates on listing availability.
Transformation needed for the price column to ensure consistency and usability as the target/response variable.
Potential transformations identified in Listings, Hosts, and Reviews tables include feature engineering based on amenities, host information, and review sentiments.
Data Quality and Checks:

Continuous variables analysis revealed the distribution and summary statistics of numerical features, highlighting any missing values and outliers.
Categorical variables analysis provided insights into the variety and frequency of different categories, identifying potential data quality issues or inconsistencies.
Data anomalies were identified and addressed, ensuring the integrity and reliability of the dataset for further analysis.
Variable Profiling and Relationships:

Correlation analysis between target (listing price) and predictor variables indicated the strength and direction of relationships, guiding feature selection and model building.
Bivariate relationships (scatter plots) illustrated the nature of associations between each predictor variable and the target variable, revealing potential linear or non-linear patterns.
Modeling Approach:

Train/test/validation splits were established to train, evaluate, and validate regression models effectively.
Linear Regression, Regression Trees, Random Forest, and Gradient Boosting Machine (GBM) were employed to explore different modeling techniques.
Model evaluation metrics (e.g., RMSE, MAE, R-squared) provided insights into the performance and predictive accuracy of each model.
Final Model Insights:

The selected final model was chosen based on its superior performance metrics, interpretability, and suitability for the problem domain.
Top 5 most important predictors were identified, indicating their significant influence on the listing price.
Direction of impact of top predictors on the response variable was interpreted, highlighting factors driving higher or lower listing prices.
These insights collectively provide a comprehensive understanding of short-term rental properties in Antwerp, empowering property owners and stakeholders to make informed decisions regarding pricing strategies, property features, and customer satisfaction.





