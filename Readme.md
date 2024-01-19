# 🏠📈 House Price Prediction
![house (Custom)](https://github.com/VISHRUT225/House-Price-Predection/assets/102377338/65a065fc-3d59-4fd5-aca1-bc3221171c4d)

## 📢 Introduction

In the current real estate market, determining the right price for a house is a complex task. The price of a house is influenced by a multitude of factors such as the type of dwelling, lot size, overall condition, year built, and more. Accurate price prediction is crucial for both buyers, who want to ensure they are not overpaying, and sellers, who aim to get the maximum possible price. It is also important for real estate agencies and online property listing platforms that need to provide reliable price estimates. However, due to the high variability and complexity of these factors, predicting house prices remains a challenging problem. The crucial part is the prediction of house prices based on various features to provide a stable and reliable estimate.

## 🎯 Objective

The overarching objective of this project is to construct a robust machine learning model tailored to accurately predict the house prices. Recognizing the multifaceted nature of real estate market, our focus extends to various key features, each contributing uniquely to the overall price.

## 📑 Dataset

The dataset utilized in this study comprises various features and a continuous target variable representing house price. The dataset is collected and loaded into a pandas DataFrame.

## 📂 Project Structure  

- `code/`: Contains the Jupyter Notebook (`House_Price_Prediction.ipynb`) with the code for data preprocessing, model development, and evaluation.
- `data/`: Placeholder for the dataset file (`House_Price_Prediction.csv`).
- `reports/`: Contains the project report (`House_Price_Prediction_Report.md`).
- `README.md`: This file, providing an overview of the project.

## 🚀 Getting Started 

This project was developed and tested using Python environment. To run the code and explore the analysis:

1. Open the Jupyter Notebook (`House_Price_Prediction.ipynb`) in your Python environment.

    [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nwsxUWQPSQom4SIfH9h7L8fElMBzQJYw?usp=sharing)

2. Execute the notebook cells sequentially to reproduce the analysis and model development.

Feel free to modify and experiment with the code to better understand the workflow and results.

## 📊 Results

The machine learning models achieved the following Mean Absolute Percentage Error (MAPE) on the test set:
- Random Forest Regressor: 19.20%
- Decision Tree Regressor: 22.96%
- Gradient Boosting Regressor: 19.16%
- K-Nearest Neighbors (KNN): 20.58%

![graph](https://github.com/VISHRUT225/House-Price-Predection/assets/102377338/1edda8ce-e41c-4f3e-b50c-41242e18270b)

Based on the performance comparison of the models, the "Gradient Boosting Regressor" has the lowest Mean Absolute Percentage Error (MAPE).

## 🤝 Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request. Issues and feature requests are also welcome!

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
