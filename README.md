# Pakistan Trade Forecasting Project

## Description

The Pakistan Trade Forecasting Project utilizes machine learning techniques to predict trade prices in Pakistan. This project employs AutoRegression (AR) and Long Short-Term Memory (LSTM) models for forecasting future trade trends. It involves advanced feature engineering techniques, including lag variables and moving averages, to enhance prediction accuracy.

## Project Components

- **Data Scraping**: Utilizes `Data_Scrapper.R` to scrape data from various websites listed in `websites_used.txt`.
- **API Conversion**: `API_to_Script.py` converts APIs to R scripts for fetching data.
- **Data Analysis**: Analyzes and visualizes the scraped data in `Project_Visualization.ipynb`.
- **Prediction and Forecasting**: Performs trade price prediction and forecasting using machine learning models in `Project_MachineLearning.ipynb`.

## Usage

1. **API Conversion**: Execute `API_to_Script.py` to convert APIs to R scripts.
2. **Data Scraping**: Run `Data_Scrapper.R` with R scripts to scrape data from specified websites.
3. **Data Analysis**: Explore `Project_Visualization.ipynb` for data analysis and visualizations.
4. **Prediction and Forecasting**: Utilize `Project_MachineLearning.ipynb` for trade price prediction and forecasting.

## Contributing

Contributions to the project are welcome! Feel free to submit bug reports or pull requests to enhance the project.

## License

This project is licensed under the [MIT License](LICENSE), allowing for free use, modification, and distribution with attribution to the original creator.
