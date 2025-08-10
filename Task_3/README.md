# 🏠 Housing Price Prediction

This project uses **Linear Regression** to predict house prices based on various features such as area, bedrooms, bathrooms, and other amenities.


# 📂 Dataset

The dataset is loaded from **Housing.csv** and should contain columns such as:

- price (Target variable)
- area
- bedrooms
- bathrooms
- stories
- mainroad
- guestroom
- basement
- hotwaterheating
- airconditioning
- parking
- prefarea
- furnishingstatus

# ⚙️ Installation
Make sure you have Python 3.7+ installed.  
Then install the required libraries:

pip install pandas scikit-learn matplotlib numpy

#How to Run
Clone this repository or download the script.
Place Housing.csv in the same directory as the script.
Run the Python script:

python housing_price_prediction.py
#📊 Model Details
Model: Linear Regression (sklearn.linear_model)

#Evaluation Metrics:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

#Preprocessing:

One-hot encoding for categorical variables

Train-test split (80% training, 20% testing)

#📈 Output
The script will print:

#✅ Model Evaluation:
MAE: <value>
RMSE: <value>