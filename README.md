# Walmart Sales Forecasting Project

## Project Overview

This project aims to address inventory management issues at a retail store with multiple outlets across the country. By analyzing historical sales data, we develop a time series forecasting model to predict sales for the next 12 weeks. The goal is to provide useful insights and forecasts to help manage inventory more effectively.

## Problem Statement

A retail store with multiple outlets across the country is facing issues in managing inventory to match the demand with respect to supply. As a data scientist, your task is to analyze the data and build prediction models to forecast sales for the next 12 weeks.

## Dataset

The dataset used in this project is `Walmart (1).csv`, which contains 6435 rows and 8 columns:

- `Store`: Store number
- `Date`: Week of sales
- `Weekly_Sales`: Sales for the given store in that week
- `Holiday_Flag`: Indicates if it is a holiday week
- `Temperature`: Temperature on the day of the sale
- `Fuel_Price`: Cost of fuel in the region
- `CPI`: Consumer Price Index
- `Unemployment`: Unemployment rate

## Project Structure

The project consists of the following steps:

1. **Introduction and Problem Statement**
2. **Loading and Exploring the Data**
3. **Data Preprocessing**
4. **Exploratory Data Analysis (EDA)**
5. **Sales Forecasting using Time Series Analysis**
6. **Model Evaluation**
7. **Conclusions and Insights**

## Usage

### Prerequisites

- Python 3.x
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
- statsmodels
- scikit-learn

### Running the Project

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/walmart-sales-forecasting.git
    cd walmart-sales-forecasting
    ```

2. Install the required packages:

    ```bash
    pip install pandas matplotlib seaborn statsmodels scikit-learn
    ```

3. Open the Jupyter Notebook:

    ```bash
    jupyter notebook Walmart_Sales_Forecasting.ipynb
    ```

4. Execute the cells in the notebook to run the analysis and forecasting.

## Results

The project includes the following analyses and results:

- Data exploration and preprocessing
- Summary statistics and visualizations of the sales data
- Time series forecasting using Exponential Smoothing
- Model evaluation using Root Mean Squared Error (RMSE)
- Insights and conclusions based on the analysis

## Conclusion

1. The historical sales data shows significant seasonality and trends.
2. Temperature and sales have a weak correlation.
3. The Exponential Smoothing model provides reasonable forecasts for the next 12 weeks.
4. Further improvement can be achieved by incorporating additional features and using more advanced models.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please contact:

- Name: [Your Name]
- Email: [your.email@example.com]
- GitHub: [yourusername](https://github.com/yourusername)

