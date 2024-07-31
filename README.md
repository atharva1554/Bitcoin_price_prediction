# Bitcoin Price Prediction

![Bitcoin](https://upload.wikimedia.org/wikipedia/commons/thumb/4/46/Bitcoin.svg/200px-Bitcoin.svg.png)

## Overview

This repository contains a project focused on predicting Bitcoin prices using various machine learning models. The goal is to analyze historical Bitcoin price data and create predictive models that can forecast future prices based on historical trends and patterns.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Data](#data)
- [Models](#models)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Bitcoin, a leading cryptocurrency, has seen significant price fluctuations since its inception. Predicting its price is a challenging task due to its high volatility and market-driven nature. This project aims to leverage machine learning techniques to predict Bitcoin prices, helping traders and investors make informed decisions.

## Project Structure

```
Bitcoin_price_prediction/
│
├── data/               # Dataset files
├── notebooks/          # Jupyter notebooks for analysis and modeling
├── scripts/            # Python scripts for data processing and modeling
├── models/             # Saved model files
├── results/            # Output results such as plots and predictions
├── README.md           # Project README file
└── requirements.txt    # List of dependencies
```

## Data

The dataset used in this project includes historical Bitcoin price data, which consists of features such as:
- Date
- Open Price
- High Price
- Low Price
- Close Price
- Volume
- Market Cap

## Models

We explored several machine learning models, including:
- Linear Regression
- Decision Trees
- Random Forest
- LSTM (Long Short-Term Memory)

Each model was evaluated based on its prediction accuracy and other relevant metrics.

## Results

The results of our models are stored in the `results/` directory. We provide visualizations of predicted vs. actual prices and detailed analysis of model performance.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/atharva1554/Bitcoin_price_prediction.git
   ```

2. Navigate to the project directory:
   ```sh
   cd Bitcoin_price_prediction
   ```

3. Create a virtual environment and activate it (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

4. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

To start using the project, you can explore the Jupyter notebooks in the `notebooks/` directory, where you will find detailed steps for data exploration, preprocessing, modeling, and evaluation.

## Contributing

We welcome contributions to enhance this project. If you have suggestions or improvements, please open an issue or submit a pull request. For major changes, please discuss them with us first.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
