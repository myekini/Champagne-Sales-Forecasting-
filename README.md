
# Machine Learning Time Series Forecasting for Perrin Freres Monthly Champagne Sales with ARIMA-And-Seasonal-ARIMA

This repository contains a machine learning project focused on time series forecasting using the ARIMA (AutoRegressive Integrated Moving Average) and SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous variables) models. The project is designed to predict monthly champagne sales for Perrin Freres, providing valuable insights into future sales trends.

## Table of Contents

- [Machine Learning Time Series Forecasting for Perrin Freres Monthly Champagne Sales with ARIMA-And-Seasonal-ARIMA](#machine-learning-time-series-forecasting-for-perrin-freres-monthly-champagne-sales-with-arima-and-seasonal-arima)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Data](#data)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Project Structure](#project-structure)
  - [License](#license)

## Project Overview

Time series forecasting plays a critical role in decision-making for businesses, and this project focuses on forecasting monthly champagne sales for Perrin Freres. The ARIMA and SARIMAX models are utilized for this task, taking into account historical sales data and potentially exogenous variables that may influence sales.

Key project objectives:

- Develop accurate time series forecasting models using ARIMA and SARIMAX.
- Evaluate model performance through appropriate metrics.
- Provide insights into future sales trends and seasonality patterns.
- Visualize forecasts and model diagnostics for better understanding.

## Data

The dataset used for this project is the monthly champagne sales data for Perrin Freres. The dataset can be found in the `data` directory as `champagne_sales.csv`. It includes the following columns:

- `Month`: The time index in month-year format.
- `Sales`: The monthly champagne sales data.

## Installation

To run the project and use the code, you need to set up your environment. Start by cloning this repository:

```bash
git clone https://github.com/yourusername/perrin-freres-champagne-forecasting.git
cd perrin-freres-champagne-forecasting
```

Then, create a virtual environment and install the required dependencies:

```bash
virtualenv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
```

## Usage

You can follow these steps to use the project:

1. Ensure you have completed the installation steps mentioned above.

2. Run the Jupyter notebooks provided in the `notebooks` directory to explore the data, build ARIMA and SARIMAX models, and make forecasts.

3. Modify the notebook to include exogenous variables if needed for SARIMAX.

4. Evaluate model performance using appropriate metrics.

5. Visualize the forecasts and model diagnostics.

6. Interpret the results and provide insights into future champagne sales trends for Perrin Freres.

## Project Structure

The project structure is organized as follows:

```
perrin-freres-champagne-forecasting/
    ├── data/
    │   ├── champagne_sales.csv
    ├── notebooks/
    │   ├── 01_Data_Exploration.ipynb
    │   ├── 02_ARIMA_Modeling.ipynb
    │   ├── 03_SARIMAX_Modeling.ipynb
    │   ├── 04_Forecasting_and_Evaluation.ipynb
    ├── src/
    │   ├── utils.py
    ├── README.md
    ├── requirements.txt
    ├── LICENSE
```

- The `data` directory contains the dataset for champagne sales.
- The `notebooks` directory contains Jupyter notebooks for data exploration, ARIMA modeling, SARIMAX modeling, and forecasting evaluation.
- The `src` directory includes utility functions used in the notebooks.
- `README.md` (this file) provides an overview of the project and instructions.
- `requirements.txt` lists the project dependencies.
- `LICENSE` specifies the project's license.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

**Note**: Ensure you replace `yourusername` in the repository URL with your actual GitHub username when cloning the repository.

For any questions or issues related to this project, please feel free to contact the project contributors.

Happy forecasting! 🍾📈