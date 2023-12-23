# My First Data Analysis Project

## Project Overview
This project is a thorough analysis of employee data to explore relationships between various factors such as monthly income, total working years, and training times. The analysis includes data cleaning, visualization, statistical analysis, and hypothesis testing to gain insights into the factors that influence employee work-life balance and income.

## Data Sourcing and Description
The dataset used in this project includes several variables such as Age, Attrition, Department, EducationField, Gender, MaritalStatus, MonthlyIncome, TotalWorkingYears, TrainingTimesLastYear, WorkLifeBalance, and YearsSinceLastPromotion. It contains 1470 observations across various departments of an organization.

## Data Preprocessing
Data preprocessing steps included:
- Outlier detection using IQR for MonthlyIncome.
- Filling missing values with appropriate strategies like median imputation for numeric columns and mode imputation for categorical columns.
- Creating dummy variables for categorical features like Gender.

## Statistical Analysis
The analysis covered:
- Correlation analysis to understand the relationship between variables.
- Descriptive statistics to summarize the data.
- Hypothesis testing to validate assumptions about the data.

## Hypotheses Tested
1. More training last year leads to higher work-life balance.
2. Significant differences exist in the mean monthly income between male and female employees.
3. Longer total working years correlate with higher total income.

## Installation and Usage
To replicate the analysis, you will need Python and the following libraries:
- openpyxl
- pandas
- seaborn
- matplotlib

## How to Run the Project
Download the `DataAnalysis.ipynb` Jupyter notebook and the dataset provided. Ensure you have the above-mentioned libraries installed and run the notebook cells sequentially to view the analysis.

## Contributions
Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request.

## License
This project is open-sourced under the MIT License.

## Contact
For any queries or discussions related to this project, feel free to contact me at [Your Contact Information].

## Acknowledgments
- Data provided by [Source of Data]
- Inspired by [References to any tutorials or articles you followed]
