OBJECTIVE:

The Energy Consumption Forecast involves analyzing a dataset to understand the relationship between electricity price and total electricity load while incorporating renewable generation data as a contextual factor. The primary goal is to identify the changes in total electricity load which might in turn influence electricity prices, with renewable generation acting as an additional feature that might affect this relationship. This analysis helps energy stakeholders, such as grid operators and policymakers, make informed decisions about energy pricing and resource allocation.

The dataset contains features such as total electricity load (total load actual), renewable generation (renewable_generation), and other potential attributes that describe weather, time, or system conditions. Since the target variable, electricity price, is continuous, the task is a regression problem, aiming to predict the price based on the given features. The analysis also explores potential correlations and insights into how renewable generation impacts energy pricing dynamics.

Our main objective is to build a predictive model to forecast energy consumption based on historical data, weather conditions. Present the results in an interactive UI where users can explore personalized recommendations to optimize their energy usage.

Output:

Built a high-accuracy energy consumption forecasting model, reducing RMSE to 0.3339 through Gradient Boosting Regressor.
Conducted EDA to analyze energy load trends, weather impact, and renewable energy contributions for better forecasting.
Deployed the model using Gradio, enabling an interactive web-based tool for real-time predictions.
