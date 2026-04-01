# E-commerce Revenue Prediction

A machine learning project that predicts whether an e-commerce session will generate revenue based on user behavior and session metrics.

## 📋 Overview

This project uses a Decision Tree classifier to predict revenue generation from e-commerce sessions. The model analyzes various user behavior metrics including page views, session durations, bounce rates, and other engagement indicators to determine if a session will result in revenue.

## 🎯 Key Features

- **Data Preprocessing**: Automated handling of numerical and categorical features
- **Class Imbalance Handling**: Balanced class weights to handle revenue vs non-revenue sessions
- **Model Pipeline**: Scikit-learn pipeline with preprocessing and classification
- **Performance Metrics**: F1-score focused evaluation with detailed classification reports

## 📊 Dataset Features

The model uses the following features:

### Numerical Features
- Administrative pages count and duration
- Informational pages count and duration  
- Product-related pages count and duration
- Bounce rates and exit rates
- Page values
- Special day indicator
- Operating systems and browser types
- Region and traffic type

### Categorical Features
- Month of the session
- Visitor type (new, returning, etc.)

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ecommerce-revenue-prediction.git
cd ecommerce-revenue-prediction
