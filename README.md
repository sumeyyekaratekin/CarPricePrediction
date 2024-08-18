# Car Prediction Project

This project is designed to predict vehicle prices using web scraping, data analysis, and machine learning techniques. It provides a comprehensive Python solution for collecting, analyzing, and forecasting vehicle prices.
Web scraping data was sourced from arabam.com, a leading automotive sales website.

## Project Overview

1. **Web Scraping**: The project utilizes libraries such as `BeautifulSoup` and `requests` to scrape vehicle prices and related information from various automotive sales websites. This phase collects data including vehicle model, make, age, mileage, and other attributes.

2. **Data Analysis**: The collected data is cleaned and analyzed using libraries like `pandas` and `numpy`. This step addresses missing values, outliers, and other data quality issues. Additionally, feature engineering and data transformation are performed in this phase.

3. **Machine Learning**: The cleaned data is processed using various machine learning algorithms provided by the `scikit-learn` library. Model performance is evaluated based on metrics such as accuracy and error rates.

4. **Neural Networks**: The project also employs deep learning techniques to build more complex models. Artificial neural networks (ANNs) are trained using `TensorFlow` and `Keras`, enhancing the model’s overall performance.

## Installation and Usage

1. **Requirements**:
    - Python 3.x
    - `beautifulsoup4`
    - `requests`
    - `pandas`
    - `numpy`
    - `scikit-learn`
    - `tensorflow`
    - `keras`

2. **Installation**:
    ```bash
    pip install beautifulsoup4 requests pandas numpy scikit-learn tensorflow keras
    ```

3. **Running the Project**:
    To run the project, first initiate the web scraping process, then proceed with data analysis and model training steps. Detailed instructions for each phase are provided in the project files.

## Project Files

- `carPricePredict_webScraping.ipynb`: Python script for web scraping operations.
- `carPricePredict_DataAnalysis.ipynb`: Python script for data analysis and cleaning.
- `carPricePredict_ML.ipynb`: Python script for machine learning model training.
- `carPricePredict_ANN.ipynb`: Python script for artificial neural network model training.
