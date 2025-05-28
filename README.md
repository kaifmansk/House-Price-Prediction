### **_🏠 Home Price Prediction Model_**
A Machine Learning-based web application for predicting the prices of residential properties using various features such as location, size, number of bedrooms/bathrooms, and more. Built using Python, Flask, and a rich dataset from Kaggle.

**📖 Overview**
This project aims to build a predictive model that estimates house prices based on features like location, size, number of bedrooms, etc. The model is trained using machine learning algorithms, including Linear Regression and Decision Trees. The final model is deployed using Flask and integrated with a frontend built in HTML and CSS.

**🎯 Objective**
To develop a robust and accurate house price prediction model that:

Assists homebuyers and sellers in making informed decisions.

Supports real estate professionals in property valuation.

Uses machine learning to estimate prices based on historic and feature-based data.

**❓ Problem Statement**
Real estate pricing is complex and influenced by numerous variables. Traditional valuation methods often fail to capture this complexity. This project addresses the challenge by:

Using ML models like Linear Regression and Decision Trees.

Training on a dataset of Bengaluru house prices.

Building a web interface for real-time predictions.

**🧰 Tech Stack**
Languages & Tools:

Python (3.7+)

Flask

HTML/CSS

JavaScript (optional for UI enhancements)

Libraries Used:

NumPy

Pandas

Scikit-learn

Matplotlib

Pickle & JSON (for model storage)

Flask (for deployment)

**⚙️ How It Works**
_Data Collection:_ Dataset sourced from Kaggle (Bengaluru House Price Data).

_Preprocessing:_ Handle missing values, feature encoding, data cleaning.

_Modeling:_ Linear Regression and DecisionTreeRegressor with evaluation metrics.

_Evaluation:_ Metrics such as MAE, MSE, RMSE.

_Deployment:_ Flask-based API for serving predictions.

_Frontend:_ HTML/CSS forms for user input.

**🖥️ Installation**
bash
git clone https://github.com/yourusername/home-price-prediction.git
cd home-price-prediction
pip install -r requirements.txt
python app.py
Access the web app at http://127.0.0.1:5000/

**▶️ Usage**
Fill in the property details (area, number of bedrooms, location, etc.).

Click Estimate Price.

The predicted price will be shown on the interface.

**🖼️ Output Samples**
_Example 1_:
Input: 2 BHK, 1000 sqft, Whitefield
Output: ₹75 Lakhs

_Example 2:_
Input: 3 BHK, 1500 sqft, Indiranagar
Output: ₹1.25 Crores

**⚠️ Limitations**
Limited to Bengaluru dataset.

Performance can vary based on dataset quality.

Model may overfit if not properly regularized.

Doesn’t account for real-time market changes.

🚀 Future Scope
Support for more cities and dynamic datasets.

Integration of real-time APIs for current market trends.

Geospatial and satellite data integration.

Mobile-friendly frontend and cloud deployment.

📄 License
This project is open-source under the MIT License.

👤 Author
Mohammad Kaif Siddiqui
B.Tech CSE (Artificial Intelligence), Jamia Hamdard University
_Email:_ kaifmansk@gmail.com
