# `Profit-Analysis(Performed Regression using Excel and Interactive Dashboard using Power-Bi)`
## Project Objective
- Perform Regression Analysis for the given data to identify how the money spent on Marketing, R&D, and Administration is affecting the company’s Profit. Predict the Profit for the below-given input features.
- Visualize the data using Tableau /PowerBI and derive insights about all the features provided and give your inputs/suggestions to the company.

## Dataset Used
<p> Profit Analysis <a href = 'https://github.com/Etishasri/Profit-Analysis/blob/main/Improvished%20profit_analysis%20sheet.xlsx'>Dataset</a></p>

## Questions or KPI's
1. What is the relationship between R&D Spend and Profit?
2. How does Marketing Spend impact Profit, and is it more significant than R&D?
3. Does Administrative Spend contribute significantly to Profit?
4. Which state (New York, California, or Florida) has the highest average profit?
5. Can we predict Profit based on R&D, Administration, and Marketing Spend?
6. Is there a diminishing return effect on Profit when increasing R&D or Marketing Spend?
7. How do combinations of Marketing and R&D investments impact Profit?
8. Are there outliers in the dataset that could skew regression analysis results?
9. How does the average Profit vary across different levels of Marketing Spend?
10. Is there a statistically significant interaction between State and the other features affecting Profit?
- <p> Dashboard Interaction <a href = 'https://github.com/Etishasri/Profit-Analysis/blob/main/Profit%20analysis.png'> View Dashboard </a></p>

## Process
1. Data Exploration: Understand the dataset by inspecting missing values, distributions, and relationships between variables.
2. Data Cleaning: Ensure no missing or invalid data points; preprocess the categorical variable "State."
3. Exploratory Data Analysis (EDA): Visualize correlations and trends between R&D Spend, Marketing Spend, Administrative Spend, and Profit.
4. Feature Engineering: Encode the "State" column into numerical values for regression modeling.
5. Split the Data: Divide the dataset into training and testing sets for model evaluation.
6. Regression Model Selection: Apply multiple linear regression to analyze the impact of features on Profit.
7. Model Evaluation: Assess the model using metrics like R-squared and Mean Squared Error (MSE).
8. Prediction: Use the model to predict Profit for the given input features.
9. Insights and Visualization: Create clear visualizations to explain the findings to stakeholders.
10. Documentation: Summarize the project results, including regression outputs, insights, and predicted values for given inputs.

## Dashboard
![Profit analysis](https://github.com/user-attachments/assets/cfa503b3-e87c-43ed-b0bb-bc72121f0a41)

## Project Insights
1. Among the analyzed variables, R&D Spend demonstrates the strongest
 correlation with Profit.
- This Indicates that the investment in R&D may have the most significant impacts on
 driving profitability compared to other factors.
2. New York emerges as the highest-performing state in terms of profitability, while
 California lags behind as the lowest-performing state.
3. Marketing spending is much higher compared to the profit it brings, while R&D
 spending gives better returns. 
4. The company spends the most on marketing, while R&D gets the least,
 suggesting that shifting some spending from marketing to R&D could improve
 profits.
5. The majority of the contribution to profit could come from R&D Spend, followed by
 Marketing, and lastly Administration.
6. Companies with a significant gap between Marketing Spend and R&D Spend
 may risk facing losses.

## Final Conclusion
The analysis highlights that R&D Spend is the most significant driver of profitability, while Marketing Spend shows diminishing returns despite being the highest expense. Shifting resources from marketing to R&D could substantially improve profits, as R&D investments yield stronger returns. New York's success in profitability should be leveraged by identifying and replicating its key contributing factors, while California's underperformance requires targeted strategies to address inefficiencies or market constraints. Optimizing marketing efforts by reallocating resources to high-performing activities and maintaining or increasing R&D investments will enhance profitability. Balancing spending, particularly ensuring Marketing Spend is equal to or less than R&D, is crucial for sustained growth and improved financial outcomes.




