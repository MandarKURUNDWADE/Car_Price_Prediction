# Car Price Prediction Using Machine Learning 🚗💰

## 📝 Description 
This project focuses on predicting the prices of used cars using machine learning algorithms. It involves utilizing a dataset containing valuable information about various car attributes and their corresponding selling prices. The project includes crucial steps like data preprocessing, model training, and evaluation.

## ⌛ Dataset 
The dataset used in this project is available in the 'car data.xls' file. It contains essential details about different car features and their respective selling prices.

## 🎯 Approach 
The project follows these key steps:
1. Data Collection & Preprocessing: Data is extracted from the 'car data.xls' file, and essential preprocessing steps are performed, such as calculating the age of the car based on the current year.
2. Outlier Removal: Outliers in the 'Selling_Price' column are eliminated to ensure better model performance.
3. Encoding Categorical Columns: The categorical columns ('Fuel_Type', 'Seller_Type', and 'Transmission') are encoded into numerical values to prepare the data for model training.
4. Feature Matrix and Target Vector: The feature matrix 'X' is created by excluding the 'Car_Name' and 'Selling_Price' columns. The response (target) vector 'y' contains the 'Selling_Price'.
5. Model Training: Four different regression models (Linear Regression, Random Forest Regressor, Gradient Boosting Regressor, and XGBoost Regressor) are trained using the preprocessed data.
6. Model Evaluation: The models' performance is evaluated using the R-squared score on the test data to assess their accuracy.

## 📥 Installations 
To run this project, ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- tkinter (for GUI)

## ⚙️ Setup 
1. Clone the repository to your local machine.
2. Install the required dependencies using the following command:
   ```
   pip install numpy pandas matplotlib seaborn scikit-learn xgboost joblib
   ```
3. Run the Jupyter Notebook file 'Car_Price_Prediction.ipynb' to perform data preprocessing, model training, and evaluation.
4. For using the GUI, execute the Python script 'car_price_prediction_gui.py' and input the car attributes for price prediction.

## 🔧 Requirements 
The project requires the following libraries:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost
- joblib
- tkinter (for GUI)

## 🚀 Technology Used 
- Python
- Jupyter Notebook
- XGBoost (Machine Learning Library)

## ▶️ Run 
To execute the project, follow the setup instructions and run the code cells in the Jupyter Notebook file. Additionally, you can use the GUI to predict car prices based on provided attributes.

---

📝 I frequently create content focused on complete projects in the realm of data science using Python and R.

💬 Feel free to inquire about data science, computer vision, Python, and R.

---

<p align="Right">(◕‿◕) Thank you for exploring my GitHub project repository. 👋</p>
