# US Home Prices Analysis Over the Last 20 Years

## Project Overview
This project aims to build a data science model to analyze key factors that influence US home prices nationally over the past 20 years. The model uses the **S&P Case-Schiller Home Price Index** as a proxy for home prices and incorporates multiple economic, demographic, and housing-related datasets to explain how these factors have impacted home price trends.

## Objectives
- **Data Collection**: Gather publicly available datasets for key factors affecting home prices.
- **Data Processing**: Clean, preprocess, and align datasets for analysis.
- **Exploratory Data Analysis (EDA)**: Identify trends, correlations, and patterns in the data.
- **Model Building**: Develop a machine learning model to explain and predict home price variations.
- **Insights**: Interpret the results to understand the impact of influencing factors.

## Datasets Used
1. **S&P Case-Schiller Home Price Index** (Target Variable):
   - Source: [FRED](https://fred.stlouisfed.org/series/CSUSHPISA)
   - Description: Monthly home price index for the US.

2. **Economic Indicators**:
   - **Unemployment Rate**: [UNRATE](https://fred.stlouisfed.org/series/UNRATE)
   - **Inflation Rate**: [CPIAUCSL](https://fred.stlouisfed.org/series/CPIAUCSL)
   - **GDP Growth**: [GDP](https://fred.stlouisfed.org/series/GDP)
   - **Mortgage Rates**: [MORTGAGE30US](https://fred.stlouisfed.org/series/MORTGAGE30US)

3. **Housing Market Data**:
   - Median Home Values: [Zillow Research Data](https://www.zillow.com/research/data/)
   - Housing Starts: [US Census Bureau](https://www.census.gov/construction/nrc/index.html)



## Project Workflow
1. **Data Collection**:
   - Gather data from reliable sources such as FRED, Zillow, US Census Bureau, and Yahoo Finance.
   - Ensure data covers a 20-year period (e.g., 2005–2025).

2. **Data Preprocessing**:
   - Clean and handle missing values.
   - Align datasets to a common time-series format.
   - Normalize and scale data as needed.

3. **Exploratory Data Analysis**:
   - Visualize trends and correlations.
   - Identify key factors influencing home prices.

4. **Model Building**:
   - Develop regression models (e.g., Linear Regression, Random Forest) or time-series models (e.g., ARIMA, LSTM).
   - Evaluate model performance using metrics like RMSE, MAE, and R-squared.

5. **Interpretation and Insights**:
   - Analyze model results to determine the impact of each factor.
   - Highlight key events influencing home price trends (e.g., 2008 financial crisis).

## Tools and Technologies
- **Python**: For data preprocessing, analysis, and modeling.
  - Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `statsmodels`, `tensorflow`.
- **Jupyter Notebook**: For interactive analysis and visualization.
- **Power BI/Tableau**: For creating professional-grade visualizations (optional).
## Results
- ![Reults of this Data ](https://github.com/Zem-0/Data-Science-Model-for-US-housing-trends-/blob/main/Screenshot%202025-01-03%20204104.png)

## Expected Deliverables
1. Cleaned and preprocessed datasets ready for analysis.
2. Visualizations showing trends and correlations.
3. A trained and validated machine learning model.
4. A report summarizing findings and insights.



## Future Enhancements
- Incorporate additional datasets such as regional home prices for more granular analysis.
- Experiment with advanced machine learning models like Gradient Boosting or Neural Networks.
- Develop a web app for dynamic visualization and prediction.

## License
This project is licensed under the MIT License. See `LICENSE` for details.

## Acknowledgments
- [Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org)
- [Zillow Research](https://www.zillow.com/research/data/)
- [US Census Bureau](https://www.census.gov)

---

