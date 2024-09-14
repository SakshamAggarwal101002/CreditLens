# CreditLens

This **Power BI Dashboard** provides insights into credit card usage, customer spending behavior, and transaction patterns. The dashboard aims to help businesses understand customer segments, track key performance metrics, and make data-driven decisions.

## Key Features
- **Transaction Overview**: Visual representation of total transactions, transaction volume, and average transaction size.
- **Customer Segmentation**: Break down of customer segments based on spending patterns, credit limits, and usage frequency.
- **Spending Behavior**: Analysis of the types of transactions (e.g., retail, online, utilities) and customer spending trends over time.
- **Risk Analysis**: Identifies potential high-risk accounts based on unusual spending behavior, late payments, or over-limit transactions.
- **Credit Utilization**: Visualizing the credit utilization rates across different customer segments.
- **Geographical Analysis**: Insights into spending trends based on regions or locations.

## Data Sources
- **Credit Card Transactions**: Historical transaction data for credit card accounts.
- **Customer Demographics**: Age, gender, income, and location data of credit card holders.
- **Account Information**: Data on credit limits, balances, and account statuses.
- **Risk Factors**: Late payments, over-limit accounts, and fraud risk indicators.

## Technologies Used
- **Power BI**: Main tool for creating interactive visualizations and reports.
- **SQL**: Used to clean and transform raw data for analysis.
- **Excel/CSV**: Data files used as inputs for the dashboard.

## Installation and Setup

1. **Prerequisites**:
    - Install **Power BI Desktop**. You can download it from [here](https://powerbi.microsoft.com/desktop/).
    - Ensure you have access to the necessary data files (e.g., transaction data, customer data).

2. **Clone the Repository**:
    ```bash
    git clone https://github.com/SakshamAggarwal101002/CreditLens.git
    cd credit-card-analysis-dashboard
    ```

3. **Open the Dashboard**:
    - Open the `.pbix` file in Power BI Desktop:
    ```bash
    open CreditLens.pbix
    ```

4. **Data Import**:
    - Ensure that the dataset paths are correct and refresh the data sources in Power BI to load the data into the dashboard.

5. **Customize**:
    - Adjust filters and customize visuals according to the analysis you want to perform.

## Usage
1. **Transaction Overview**: View the total number of transactions, monthly trends, and top transaction categories.
2. **Customer Segmentation**: Analyze different customer groups based on credit usage, spending frequency, and credit limit.
3. **Spending Patterns**: Track spending behavior, including top merchants, spending by category, and average transaction size.
4. **Risk Monitoring**: Visualize accounts with high risk, including late payments, high credit utilization, and over-limit warnings.
5. **Geographical Trends**: Analyze credit card usage by region, city, or specific merchant locations.

## Dashboard Walkthrough
- **Main Page**: Provides a high-level summary of all key metrics, including total transaction volume, average credit utilization, and spending categories.
- **Segmentation Page**: Visualizes customer segmentation based on their spending patterns and credit utilization rates.
- **Risk Analysis Page**: Focuses on identifying risky accounts based on late payments, over-limit usage, and unusual spending.
- **Geographical Insights**: Shows a map of spending by region, highlighting key areas where spending is concentrated.

## Future Enhancements
- Integrate real-time data for live updates on transactions.
- Add predictive analytics to forecast credit card usage and potential risks.
- Implement machine learning models to predict customer churn or fraud.



