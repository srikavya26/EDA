### Exploratory Data Analysis (EDA) 
#### Project Overview
This project encompasses two major components: Exploratory Data Analysis (EDA) on a sales dataset and predictive modeling using XGBoost on health statistics data. The aim is to extract valuable insights from the sales data and to develop a robust predictive model for health outcomes using XGBoost.
#### Background
Exploratory Data Analysis (EDA) is a crucial step in the data science workflow that involves summarizing the main characteristics of a dataset, often using visual methods.
XGBoost (Extreme Gradient Boosting) is a powerful machine learning technique that has gained popularity for its efficiency and performance in predictive modeling. Health statistics encompass a wide range of data, including patient records, epidemiological data, and other health-related metrics. By applying XGBoost to this data, we aim to enhance the accuracy of health predictions and provide actionable insights for healthcare providers and policymakers.
#### Libraries Used
- pandas: For data manipulation and analysis.
- seaborn: For statistical data visualization.
- matplotlib.pyplot: For creating static, animated, and interactive visualizations.
- calmap: For creating heatmaps of time series data.
- pandas_profiling: For generating a detailed profile report of the dataset.
#### Results and Insights
- Performed univariate analysis to understand the distribution and central tendency of individual variables.
- Conducted bivariate analysis to explore relationships between pairs of variables, such as sales by product and region.
- Predictive modeling to forecast future sales trends.
- Time series analysis revealed seasonal sales trends.
- Correlation analysis identified key factors affecting sales and the strength of their relationships.
- Product category and region significantly influence sales patterns.
####  Profile Report
##### A comprehensive profile report is generated using pandas_profiling, providing an in-depth overview of the dataset including:
- Dataset overview.
- Variable types and their distributions.
- Missing values and data quality.
- Descriptive statistics.
#### Model Development
- Implement XGBoost using Python and relevant libraries (e.g., XGBoost, Scikit-learn).
- Split the data into training and testing sets to validate the model’s performance.
- Model Training and Optimization
- Train the XGBoost model on the training dataset.
- Optimize hyperparameters using techniques such as grid search or random search to enhance the model’s accuracy and prevent overfitting.

#### Getting Started
#### Prerequisites
- Ensure you have Python 3.x installed along with the following libraries:
``` bash
pip install pandas seaborn matplotlib calmap pandas-profiling
!pip install xgboost
```
#### Running the Analysis
#### Clone the Repository

``` bash
git clone https://github.com/srikavya26/EDA.git
cd EDA
```
##### Jupyter Notebook
- Open the EDA.ipynb notebook in Jupyter to explore the EDA step-by-step.

*Profile Report*
- Open the Sales_Profile_Report.html in a web browser to view the detailed profile report of the sales dataset.
<img width="1280" alt="Screenshot 2024-06-10 at 12 52 22" src="https://github.com/srikavya26/EDA/assets/95865936/f172448b-fb35-4e81-8926-54d7f18ffb61">
<img width="1280" alt="Screenshot 2024-06-10 at 13 58 44" src="https://github.com/srikavya26/EDA/assets/95865936/4d62bfcf-66b3-490e-b168-04cf7fe24250">

<img width="1280" alt="Screenshot 2024-06-10 at 12 52 32" src="https://github.com/srikavya26/EDA/assets/95865936/41551062-9dc4-4ea3-9682-9b08ed9bac8f">

#### Conclusion
This EDA provides valuable insights into the sales data, aiding in data-driven decision-making and strategic planning. The visualizations and detailed profile report enhance the understanding of sales dynamics, helping stakeholders to identify key trends and patterns.The XGBoost predictive model developed in this project provides a powerful tool for forecasting health outcomes, demonstrating the potential of machine learning in transforming healthcare practices.



