# Bank Customer Churn Analysis

## Project Overview
This project aims to analyze customer churn within a banking institution by examining customer attributes and transaction history. The primary goal is to identify key factors influencing churn and develop actionable insights to enhance customer retention strategies.

## Dataset
### Data Transformations
- `Age`, `Balance`, and `Credit Score` columns were categorized into groups for easier aggregation and analysis.
- The `Exited` column was transformed from integer values (0 or 1) to categorical values (`Churned` or `Not Churned`) for better readability.
- Similar transformations were applied to `NumOfProducts`, `HasCrCard`, and `IsActiveMember` to improve data interpretation.
- The raw dataset is included in this repository.

**Filename:** `Bank Customer Churn Analysis.csv`

### Features
- `CustomerID`: Unique identifier for each customer
- `Age`: Age of the customer
- `Gender`: Male or Female
- `Geography`: Customer's country of residence
- `Tenure`: Number of years as a bank customer
- `Balance`: Customer's account balance
- `Products`: class of bank products the customer is subscribed to
- `HasCrCard`: Indicates if the customer owns a credit card (1 = Yes, 0 = No)
- `IsActiveMember`: Indicates if the customer is an active member (1 = Yes, 0 = No)
- `EstimatedSalary`: Estimated annual salary of the customer
- `Exited`: Indicates if the customer has churned (1 = Yes, 0 = No)

## Key Insights
- **Churn Rate Analysis**: Identified the percentage of customers leaving the bank and associated trends.
- **Demographic Impact**: Noted variations in churn rates based on geography, age groups, and gender.
- **Balance & Tenure Influence**: Analyzed how balance levels and customer tenure correlate with churn likelihood.
- **Customer Engagement**: Observed that active customers have significantly lower churn rates.
- **Product Utilization**: Found that customers with fewer subscribed products are more likely to churn.

## Tools Used
- **Power BI**: Developed interactive dashboards and visualizations.
- **Python (Pandas, Matplotlib, Seaborn)**: Performed data cleaning, preprocessing, and exploratory data analysis.
- **SQL**: Utilized for efficient data querying and transformation.

## How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/bank-churn-analysis.git
   ```
2. Open the `Bank Customer Churn Analysis.csv` file in your preferred data analysis tool (Excel, Python, SQL, or Power BI).
3. If using Power BI, open the `.pbix` file to explore the pre-built visualizations.
4. Execute the provided Python scripts or Jupyter notebook (if available) to perform additional data analysis.

## Future Enhancements
- Develop predictive models using machine learning techniques to forecast customer churn.
- Expand the dataset with additional behavioral attributes for deeper analysis.
- Deploy an interactive web-based dashboard using Tableau or Streamlit.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request with suggested improvements.

## License
This project is licensed under the MIT License.



