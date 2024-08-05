# Store_Sales_Predictions
This is a time series regression analysis, where models are built to predict sales or give forecast of sales for a grocery firm

# Aim and Objective
The primary focus of this project is to utilize time series regression analysis to forecast sales for Corporation Favorita, a prominent grocery retailer based in Ecuador.

The objective is to develop a robust model capable of accurately forecasting future sales by leveraging the extensive time series data of thousands of products sold across various Corporation Favorita locations. The resulting forecasts will provide valuable insights to the store's management, enabling them to formulate effective inventory and sales plans.

I will utilize the CRISP-DM framework to execute the project.

 ## Project Overview 🖼

The project includes the following stages:

### 1. 📥 Data Collection

- Azubi Africa's SQL Server database, GitHub repository and OneDrive.

N/B: The datasets from the sources above where saved in the root folder of this repository for easy access

### 2. 📚 Data Loading

- Utilizing `pyodbc` for SQL data
- Leveraging `pandas` for CSV and Excel files

### 3. 💡 Exploratory Data Analysis (EDA)

- Merging
- Duplicate checks
- Handling missing values
- Renaming Columns and Changing Datatypes
- Creating new features
- Visualizations
- Hypothesis testing
- ADF Testing

### 4. 📈 Answering Questions with Visualizations

**Visualization Tools:**

- Matplotlib
- Seaborn

### 5. ⚙️ Feature Engineering

- Data Splitting
- Feature Encoding with OneHotEncoder
- Feature Scaling with MinMaxScaler

### 6. ⌛ Model Training

- Linear Regression
- XGBoost
- CatBoost
- AutoReg
- ARIMA
- SARIMA

### 7. 📊 Model Evaluation

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Squared Logarithmic Error (MSLE)
- Root Mean Squared Logarithmic Error (RMSLE)

### 8. 🎯 Hyperparameter Tuning

- RandomSearchCV

### 9. 🤔 Prediction on Validation Set

### 10. 📒 Prediction on Test Dataset

### 11. 💭 Exportation

- os
- pickle
- save_model


# Getting Started

1. **Clone the Repository:** `git clone [repository_url]`
2. **Install Dependencies:** `pip install -r requirements.txt`
3. **Run the Analysis Script:** `python analysis.py`

# Usage

- **Customize and Explore:** Tailor the analysis to your needs, and dive deep into the `notebooks` for in-depth insights.

# Join the Expedition ⚔️

# Contributions

Dare to be part of the adventure! Contribute and leave your mark on this epic journey:

1. **Fork the Repository.**
2. **Create a New Branch:** `git checkout -b feature_branch`
3. **Make Changes and Commit:** `git commit -m 'Add feature'`
4. **Push to the Branch:** `git push origin feature_branch`
5. **Submit a Pull Request.**


# Article on Medium
https://medium.com/@joojoakorful/demand-forecast-optimization-for-corporation-favorita-a-time-series-regression-ml-approach-655f61642cba

##  Acknowledgements
Thanks to Azubi Africa and their instructors for guidng us through this journey.Special mention to Glen Anum,Rachel Appiah-Kubi and Portia Bentum.Also thanks to my team mates who helped in diverse way.Thanks to Sena Aku and Elisha Stanley.Thanks to my family and everyone who supported.



## License
This project operates under the [MIT License](LICENSE.md).

## Unlock Secrets 🧐

### Additional Information

For inquiries or deeper insights, contact our fearless explorer:

**Author:** Glenn Desmond Rockson  
**Email:** [joojoakorful@gmail.com]