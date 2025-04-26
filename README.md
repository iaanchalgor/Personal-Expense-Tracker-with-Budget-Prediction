# Personal-Expense-Tracker-with-Budget-Prediction


Overview: This project aims to help individuals track their personal expenses and predict future spending using machine learning. It predicts the user's upcoming expenses based on historical data and gives insights into potential savings. By categorizing expenses such as groceries, transport, entertainment, healthcare, and more, this tool helps users understand their spending patterns and manage their finances more effectively.

Features:

Expense Tracking: Tracks user expenses across different categories such as groceries, transport, healthcare, and more.

Budget Prediction: Uses machine learning (Linear Regression) to predict the next month's total expenses based on historical data.

Categorized Spending: Automatically categorizes spending into predefined categories (e.g., groceries, transport, etc.) based on transaction text.

Savings Insights: Provides insights into potential savings in various categories and gives predictions for future savings based on historical trends.

Data Visualization: Displays the actual vs. predicted expenses through a Bar Chart to visually compare the user's spending behavior.

Dataset: The dataset consists of several features that represent a user’s financial information. The columns in the dataset include:

Income: User's monthly income.

Age: User's age.

Dependents: Number of people dependent on the user (e.g., family members).

Occupation: User's job type (e.g., Engineer, Teacher, etc.).

City Tier: The tier of the city the user lives in (Tier 1, Tier 2, etc.).

Rent: User's monthly rent payment.

Loan Repayment: Monthly loan repayment amount.

Insurance: Insurance expenditure.

Spending Categories: Various categories like Groceries, Transport, Eating Out, Entertainment, Healthcare, etc.

Desired Savings: The amount the user wishes to save every month.

Process:

Data Preprocessing:

Label Encoding: For categorical columns like Occupation and City_Tier, the data is converted into numerical values using label encoding.

Feature Engineering: New columns like Total Expense, Total Potential Savings, and Effective Income are created.

Model Training:

A Linear Regression model is used to predict the total expenses. The model is trained using features like Income, Age, Dependents, and Effective Income.

Prediction:

The trained model predicts the total expenses (using the input features) for the upcoming month.

Evaluation:

The model’s accuracy is evaluated using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and the R² Score to check how well the model fits the data.

Visualization:

The actual and predicted expenses are compared using a Bar Chart for easy visualization and analysis.

Outcome: The model predicts the total expenses based on past spending data and offers insights into future expenses. This helps users make informed decisions about their spending and savings. Users can also get suggestions on areas where they could potentially save more.



Income and Age are key factors influencing the predicted expenses.

The model’s accuracy can be improved by including more data and using advanced machine learning models.

The visualization of predicted vs. actual expenses provides a clear picture of how well the model is performing.
