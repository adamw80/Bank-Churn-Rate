# NYC Housing Pricing Analysis

## Overview
This project analyzes housing prices in New York City using exploratory data analysis (EDA) and predictive modeling. By understanding key factors such as property type, square footage, and location, the project builds and fine-tunes an XGBoost model to accurately predict housing prices.

## Dataset
The dataset contains various features related to housing prices, including:
- **BROKERTITLE:** Title of the broker.
- **TYPE:** Type of the house (e.g., condo, single-family home).
- **PRICE:** Price of the property.
- **BEDS:** Number of bedrooms.
- **BATH:** Number of bathrooms.
- **PROPERTYSQFT:** Property square footage.
- **ADDRESS:** Full address of the property.
- **STATE:** State where the property is located.
- **LATITUDE:** Latitude coordinate of the property.
- **LONGITUDE:** Longitude coordinate of the property.

## Key Objectives
1. Perform EDA to explore trends and patterns in housing prices.
2. Identify key features that influence housing costs.
3. Build and fine-tune an XGBoost model to predict property prices.

## Project Structure
```
.
├── README.md                 # Documentation file
├── Housing_Cost_with_XGBoost.ipynb  # Main analysis and prediction notebook
├── data/                     # Contains the input housing dataset
├── results/                  # Outputs such as plots, tables, and model performance
└── models/                   # Saved XGBoost models and scripts
```

## Key Features
- **Exploratory Data Analysis:** Uncover trends in housing prices and key influencing factors.
- **XGBoost Model Training:** Build and optimize a model to predict prices accurately.
- **Feature Importance:** Analyze which features have the most impact on property prices.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/nyc-housing-pricing.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open and execute the `Housing_Cost_with_XGBoost.ipynb` notebook in a Jupyter environment to follow the analysis and model training.

## Results
- Insights into the factors influencing housing prices in NYC.
- Visualizations highlighting property trends.
- XGBoost model predictions and performance evaluation.

## License
This project is licensed under the MIT License.

## Contact
For questions or feedback, feel free to reach out:
- **Email:** Adam.RivardWalter@gmail.com  
- **GitHub:** [adamw80](https://github.com/adamw80)
