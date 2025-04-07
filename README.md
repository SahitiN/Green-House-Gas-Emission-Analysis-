# GHG Emissions Analysis and Forecasting

This project presents an end-to-end analysis and forecasting of Greenhouse Gas (GHG) emissions using linear regression. The goal is to identify key contributing factors to GHG emissions and develop a model for predicting emissions based on available features.

## 📊 Project Overview

The notebook performs the following steps:
- Loads and explores the GHG dataset.
- Cleans and preprocesses the data.
- Performs feature engineering and selection.
- Builds a linear regression model to predict GHG emissions.
- Evaluates model performance using R² and MAE metrics.
- Visualizes actual vs predicted emissions and residuals.

## 🔧 Technologies Used

- **Python**  
- **Pandas** for data manipulation  
- **Scikit-learn** for regression modeling and evaluation  
- **Matplotlib & Seaborn** for data visualization  
- **Jupyter Notebook** for interactive development  

## 🧪 Installation

To run this project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ghg-analysis.git
    cd ghg-analysis
    ```

2. (Optional) Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the notebook:
    ```bash
    jupyter notebook GHG\ Analysis.ipynb
    ```

## 📈 Model Performance

- **R² Score**: ~0.87  
- **Mean Absolute Error (MAE)**: ~13.2  
- Residual plots indicate low bias and a fairly even distribution of errors.


## 📌 Future Work

- Experiment with other models (Random Forest, XGBoost)
- Perform time series forecasting
- Incorporate external variables like policy data or climate events




