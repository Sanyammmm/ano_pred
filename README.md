Product Sales Prediction Model
This repository contains a machine learning model designed to predict the sales of a product based on a range of input features. The model leverages historical sales data and advanced machine learning algorithms to provide accurate sales forecasts, which can assist businesses in decision-making, inventory management, and marketing strategies.

Features
Accurate Sales Prediction: The model uses supervised learning techniques to predict future sales based on historical data.
Scalable: Easily adaptable to various products and industries.
Customizable: Flexible feature engineering to incorporate additional data points like seasonal trends, marketing spend, or competitor data.
Data Preprocessing: Automated cleaning, transformation, and feature selection to prepare the data for accurate modeling.
Model Evaluation: Performance metrics including RMSE, MAE, and R² for model evaluation.
Dataset
The model was trained on a dataset containing the following features:

Date: The date of the sales record.
Product ID: Unique identifier for the product.
Sales: The number of units sold.
Price: The price of the product at the time of sale.
Promotion: Whether a promotion was active during the sales period.
Holiday: Whether the sale occurred during a holiday season.
You can customize the dataset to include any relevant features that may affect sales predictions.

Model : Random Forest Regressor, XGBRFRegressor
The model was trained using Python with the following libraries:

scikit-learn
pandas
numpy
matplotlib/seaborn (for visualization)
joblib (for model persistence)
