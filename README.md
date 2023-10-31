# Product-Demand-Prediction
NAAN MUDHALVAN IBM-Product demand prediction
# Product Demand Prediction Using Machine Learning

This README file provides instructions on how to run the code for product demand prediction using machine learning, specifically with the dataset you mentioned. Please follow the steps below to set up and execute the project.

Data Source:([https://www.kaggle.com/datasets/chakradharmattapalli/product-demand-prediction-with-machine-learning](https://www.kaggle.com/datasets/chakradharmattapalli/product-demand-prediction-with-machine-learning))

# How to run the code and any dependency:
       Product demand Prediction using Machine Learning

# How to Run:
intall jupyter notebook in your commend prompt
         #pip install jupyter lab
         #pip install jupyter notebook (or)
                  1.Download Anacoda communiting software for desktop
                  2.install the anaconda community
                  3.Open juyter notebook
                  4.Type the code & execute the given code                 

## Table of Contents
1. [Introduction](#introduction)
2. [Data Source](#data-source)
3. [Dependencies](#dependencies)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Data Preparation](#data-preparation)
7. [Training the Model](#training-the-model)
8. [Making Predictions](#making-predictions)
9. [Additional Resources](#additional-resources)

## 1. Introduction

This project is designed to predict product demand using machine learning. It includes a pre-built machine learning model that uses historical data to make predictions about future product demand.

## 2. Data Source

The dataset used for this project, 'ProductDemand.csv', was sourced from [kaggle.com](https://www.kaggle.com/). It contains information about product demand including unique identifiers (`ID`), store details (`Store ID`), pricing information (`Total Price` and `Base Price`), and sales data (`Units Sold`). 

## 3. Dependencies

Before running the code, ensure that you have the following dependencies installed on your system:

- Python 3.11 or later
- Pip (Python package manager)

we can install the required Python packages by running the following command:

```bash
pip install -r requirements.txt
```

## 4. Installation

1. Clone this repository to your local machine.

```bash
git clone https://github.com/Dhanulesh/Product-Demand-Prediction.git
```

2. Navigate to the project directory.

```bash
cd product-demand-prediction
```

## 5. Usage

The project consists of the following main components:

- Data Preparation
- Model Training
- Prediction

Follow the steps below to utilize each component:

## 6. Data Preparation

Before running the model, you need to prepare your data. The dataset should be in CSV format and include the following columns:

- `ID`: Unique identifier for each data point
- `Store ID`: Unique identifier for the store
- `Total Price`: The total price of the product
- `Base Price`: The base price of the product
- `Units Sold`: The number of units sold

You can customize the dataset to fit your needs. Make sure to place your dataset in the `data/` directory with the name 'ProductDemand.csv'.

## 7. Training the Model

To train the model with your data, you can use the `train.py` script. Make sure you have prepared your dataset as described in step 6.

Run the following command to train the model:

```bash
python train.py --data_path data/PoductDemand.csv
```

The script will save the trained model to the `models/` directory.

## 8. Making Predictions

To make predictions using the trained model, you can use the `predict.py` script. Modify the `input_data.csv` file in the `data/` directory to include the data points for which you want to make predictions.

Run the following command to make predictions:

```bash
python predict.py --model_path models/your_model.pkl --input_data data/input_data.csv
```

The script will generate predictions and save them to the `predictions/` directory.

## 9. Additional Resources

- If you encounter any issues or have questions, please refer to the documentation or the README file in the repository.
- For more advanced usage and customization, you can explore the code in the repository.

MIT License

Copyright (c) 2023 [Dhanulesh.S]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS," WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE, ARISING FROM, OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

