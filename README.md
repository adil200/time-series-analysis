
# Time Series Analysis with LSTM
Welcome to the "Time Series Analysis with LSTM" repository! This project focuses on performing time series analysis and predicting future values using LSTM (Long Short-Term Memory) neural networks.

## Overview

In this repository, you will find a Jupyter Notebook (`timeseries.ipynb`) that demonstrates how to perform time series analysis and predictions using LSTM networks. The notebook uses historical Google stock price data from the `Google Dataset.xlsx` file and preprocesses it for training. It then creates sequences of historical data and corresponding labels for training an LSTM model. The trained model is used to make predictions on test data, and the accuracy of the predictions is evaluated.

## Installation

To run the code in the notebook, you'll need the following dependencies:

- Python 3.
- Numpy
- Pandas
- TensorFlow
- Scikit-learn
- Jupyter Notebook

You can install these dependencies using the following command:

```bash
pip install numpy pandas tensorflow scikit-learn jupyter
```
## Usage

1.  Clone this repository:
```bash
git clone https://github.com/adil200/time-series-analysis.git` 
```
2.  Download the dataset (`Google Dataset.xlsx`) and place it in the root directory of the project.
    
3.  Launch Jupyter Notebook and open the `timeseries.ipynb` notebook.
    
4.  Follow the instructions in the notebook to explore time series analysis and LSTM-based predictions.
    

## Results

After training and evaluating the model, you can observe the following results:

-   Training Loss: `0.0022`
-   Test Loss: `0.0023`
-   Accuracy: `94.45%`

## Acknowledgments

The code and techniques used in this project are inspired by various tutorials and resources on time series analysis and LSTM networks.
