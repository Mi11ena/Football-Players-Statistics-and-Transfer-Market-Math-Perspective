```markdown
# Football Players Statistics
# Transfer Market Math-Perspective
HSE Third Year Terms Project

This project, "Football Players’ Statistics and Transfer Market: Math Perspective," aims to revolutionise the valuation of football players by leveraging machine learning techniques. By analyzing comprehensive datasets from the Transfermarkt website, the project seeks to develop robust predictive models that can accurately forecast player market values. The initiative addresses key areas including data preprocessing, regression analysis, and anomaly detection, aiming to enhance transfer market efficiency and mitigate financial risks.

The project encompasses several critical stages: data collection and parsing using tools like BeautifulSoup, preprocessing to ensure data quality, and feature encoding for relevant player attributes. A RandomForestRegressor is employed to predict player transfer values, optimised using the hyperparameter tuning framework Optuna. Additionally, the project identifies pricing anomalies using an XGBClassifier and addresses the inherent class imbalance with techniques like SMOTE and RandomForestClassifier.

Initial results indicated significant gaps between predicted and actual market values, highlighting the need for model enhancement. Despite improvements through optimisation and resampling techniques, the model's reliability in real-world applications remains limited due to dataset imbalances. Future work will focus on refining these models and exploring more sophisticated methods to better handle data disparities and improve prediction accuracy.

This project ultimately aims to provide a data-driven framework for player valuation, offering valuable insights for clubs, agents, investors, and sports enthusiasts, thereby contributing to more informed decision-making in the football industry.

**Project Purpose**: Building a predictive model for the transfer value of football players.

## Files and Notebooks

- **final_dataset.xlsx**: The dataset obtained after parsing data with colleagues and preprocessing.
- **Parsing NationalTeam.ipynb**: A notebook containing functions for parsing information about a player’s performances in the national team by his URL.
- **NationTeam_Trophies.ipynb**: A notebook to run the preprocessing process for trophies and statistics in the national team.
- **Positions.ipynb**: A notebook to run the preprocessing process for positions.
- **PricePrediction.ipynb**: A notebook to start the process of training the RandomForestRegressor model on the collected dataset.
- **rf_model.joblib**: The best model obtained by training models from the file "PricePrediction.ipynb".
- **ExploreAnomaly.ipynb**: A notebook which runs the classification to identify anomalies in the player's price.
```
