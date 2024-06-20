# House Price Prediction

This repository contains Python code for predicting house prices using advanced regression techniques. The project focuses on preprocessing data, exploring various features, applying machine learning models, and optimizing predictions.

## Project Structure

- **`Data/`**: Directory containing datasets used for training (`train.csv`), and testing (`test.csv`).
- **`requirements.txt`**: File listing all required Python libraries and dependencies.
- **`house_price_prediction.ipynb`**: Jupyter notebook containing the main code for data preprocessing, model building, and evaluation.

## Description

This project aims as a solution for this [problem](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) to predict house prices using a dataset that includes various features such as lot size, neighborhood, number of rooms, and more. The steps involved in the project are as follows:

1. **Data Preprocessing**:
   - Importing and cleaning datasets.
   - Handling missing values and outliers.
   - Feature engineering to create new meaningful features.

2. **Exploratory Data Analysis**:
   - Visualizing relationships between features and target variable (`SalePrice`).
   - Analyzing distributions and correlations among variables.

3. **Model Building**:
   - Implementing machine learning models including:
     - Random Forest, Gradient Boosting, Ridge Regression, Lasso Regression, Support Vector Regression (SVR), XGBoost, LightGBM, CatBoost.
   - Hyperparameter tuning using Randomized Search Cross Validation.

4. **Ensemble Learning**:
   - Stacking multiple optimized models for improved prediction accuracy.

5. **Evaluation and Submission**:
   - Generating predictions using the ensemble model.
   - Formatting predictions according to submission requirements.

## Requirements

All Python libraries and dependencies required for running the code are listed in `requirements.txt`. Install them using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Assem-ElQersh/Kaggle-Housing-Prices-Prediction
   cd Kaggle-Housing-Prices-Prediction  
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook `house_price_prediction.ipynb` to execute the code step-by-step.

4. The final predicted house prices will be saved in `my_prediction_ensemble.csv`.

## Contributors

- [Assem ElQersh](https://github.com/Assem-ElQersh)
  
This Repo is mainly inspired by the [Solution of gvndkrishna](https://github.com/gvndkrishna/Kaggle-House-Price-Prediction) 

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](https://github.com/Assem-ElQersh/Kaggle-Housing-Prices-Prediction/blob/main/LICENSE) file for details.
