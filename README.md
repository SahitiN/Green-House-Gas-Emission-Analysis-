# GHG Emissions Analysis and Forecasting

Managing greenhouse gas emissions is a critical step in tackling climate change. Gaining a deep understanding of emission patterns and their driving factors is essential for shaping impactful environmental policies. This project is driven by the need to leverage historical emissions data to uncover trends, disparities, and shifts across various sectors and substances.

We focus on analyzing [global emissions data](https://edgar.jrc.ec.europa.eu/report_2023) from 1970 to 2022 to reveal overarching patterns and identify the major contributors to emissions worldwide. Our objective is to track how these emissions have evolved over time, assess the influence of past policies, and highlight key sectors where emission reductions are most urgent.

Ultimately, this project aims to offer data-backed insights and strategic recommendations that can support policymakers and organizations in designing more effective solutions to mitigate global emissions.

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




