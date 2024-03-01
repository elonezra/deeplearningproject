# Bitcoin Price Prediction

## Project Overview
This project is about predicting the 'Open_Close_Gap' in Bitcoin prices using historical data from 2014 onwards. The 'Open_Close_Gap' is the difference between the opening and closing prices of Bitcoin on a given day. The aim is to build a model that can accurately predict this gap.

We compare the performance of three different models: a dummy model, an Artificial Neural Network (ANN), and a Linear Regression model. The dummy model serves as a baseline, providing a point of reference for the performance of the other two models. The ANN and Linear Regression models represent two different approaches to predictive modeling, with the ANN leveraging the power of deep learning.

## Getting Started

### Prerequisites
Before running the code, you need to have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- tensorflow
- sklearn

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn tensorflow sklearn
### Running the Code
To run the code, simply navigate to the directory containing the Python scripts and run them using the Python command. For example:

```bash
python script_name.py
Replace `script_name.py` with the name of the script you want to run.

## Project Structure
The project is structured as follows:

- **Data Preprocessing**: The data is first loaded and preprocessed. This includes handling missing values, converting data types, and normalizing the data.
- **Model Training**: The Linear Regression and ANN models are trained using the preprocessed data. The models are trained using cross-validation to ensure robust and reliable performance.
- **Model Evaluation**: The models are evaluated on a test set that was not used during training. The performance of the models is compared using R-Squared scores and Mean Squared Error (MSE).
- **Results Visualization**: The results are visualized using various plots, including correlation heatmaps and pairplots.

## Results
Both the Linear Regression and ANN models showed promising results in predicting the 'Open_Close_Gap' in Bitcoin prices. The ANN model slightly outperformed the Linear Regression model, demonstrating the potential of deep learning for this task. Despite the inherent volatility and unpredictability of Bitcoin prices, this project shows that machine learning can provide valuable insights and predictions in the world of cryptocurrency.

## Future Work
Future work could involve tuning the model parameters and exploring different model architectures to improve the results. Other machine learning techniques could also be explored, such as ensemble methods or time series models.
