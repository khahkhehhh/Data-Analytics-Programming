
# DATA THEME: CLIMATE CHANGE

# Annual Greenhouse Gas (GHG) Air Emissions Accounts

## Dataset Overview

The 'Annual Greenhouse Gas (GHG) Air Emissions Accounts' dataset contains 1186 records and 27 columns downloaded from the International Monetary Fund's Climate Change Dashboard website. It provides insights into annual GHG emissions by activity and region, featuring identifiers, descriptors, and detailed information for the Climate Tracking System (CTS).

### Dataset Attributes

- **ObjectId2**: Identifier for the record
- **Country**: Name of the country
- **ISO2**: Two-letter country code
- **ISO3**: Three-letter country code
- **Indicator**: Type of greenhouse gas emission indicator
- **Unit**: Measurement unit for emission data
- **Source**: Source of the emission data
- **CTS_Code**: Code for the Climate Tracking System
- **CTS_Name**: Name of the Climate Tracking System
- **CTS_Full_Descriptor**: Detailed descriptor for the Climate Tracking System
- **Industry**: Industry associated with the emission data
- **Gas_Type**: Type of greenhouse gas
- **Seasonal_Adjustment**: Information on seasonal adjustment
- **Scale**: Measurement scale for the emissions data
- **F2010 to F2022**: Annual greenhouse gas emissions data for each year

## Research Questions

1. Can machine learning models accurately predict a country's greenhouse gas emissions for the year 2022 based on historical data from 2013 to 2021?
2. How well can machine learning models differentiate between normal emission patterns and anomalies?
3. How well does the model predict annual greenhouse gas (GHG) emissions for the year 2022 based on historical data from the year 2013?
4. How well can machine learning models differentiate between various countries based on their greenhouse gas emissions, considering different gas types and industries?
5. Which features have the most significant impact on predicting greenhouse gas emissions in a country?
6. Can we classify countries into different groups or clusters and observe patterns in their greenhouse gas emissions over the years, using clustering algorithms?
7. Can machine learning classify emissions patterns for different gas types?

## Insights

### Key Findings

- **Predicting GHG Emissions**: Utilized Linear Regression model with reasonable accuracy.
- **Anomaly Detection**: Employed Isolation Forest model to detect anomalies.
- **Predicting GHG Emissions for 2022 from 2013**: Achieved high predictive accuracy using Linear Regression.
- **Differentiating Countries Based on GHG Emissions**: Used Decision Tree Classifier with limited accuracy.
- **Impact of Features on GHG Emissions**: Conducted feature importance analysis using Random Forest Regressor.
- **Clustering Based on ISO Codes**: Employed K-means clustering to group countries based on regional similarities.
- **GHG Emissions by Gas Types**: Utilized Random Forest Classifier with insights into classification of emissions based on gas types.

## Python and Machine Learning

Python was extensively used for data preprocessing, exploratory data analysis, and machine learning modeling. Libraries such as pandas, scikit-learn, and matplotlib were employed for data manipulation, model building, and visualization. Machine learning algorithms including Linear Regression, Isolation Forest, Decision Tree Classifier, Random Forest Regressor, and K-means clustering were applied to analyze and predict greenhouse gas emissions.
