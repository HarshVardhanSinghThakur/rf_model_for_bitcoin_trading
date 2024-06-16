# RF Model for Bitcoin Trading

This repository contains a machine learning model that predicts Bitcoin market movements using a Random Forest classifier. 
The model is designed to forecast the direction of the Bitcoin market in the next interval and execute trades based on the provided strategy using the Backtrader library.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data Preparation](#data-preparation)
- [Model Training](#model-training)
- [Backtesting Strategy](#backtesting-strategy)


## Introduction

This project aims to predict the movement of the Bitcoin market using historical data and a Random Forest model. The predictions are then used to execute trades in a simulated environment using Backtrader, a Python library for backtesting trading strategies.

## Features

- Market movement prediction using Random Forest
- Backtrader integration for backtesting trading strategies
- Customizable trading strategy
- Performance metrics for model evaluation

## Installation

To get started, clone this repository and install the necessary dependencies:

```bash
git clone https://github.com/yourusername/rf_model_for_bitcoin_trading.git
cd rf_model_for_bitcoin_trading
pip install -r requirements.txt
