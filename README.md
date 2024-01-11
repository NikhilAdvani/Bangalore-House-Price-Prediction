# Bangalore House Price Prediction

This project focuses on predicting house prices in Bangalore using a dataset sourced from Kaggle. The dataset contains various features such as location, size, total_sqft, bath, balcony, and price. The goal is to build a machine learning model that accurately predicts house prices based on these features.

## Project Overview

1. **Dataset Cleaning:**
   - Removed unnecessary columns like 'area_type' and 'availability'.
   - Handled missing and non-numeric values.
   
2. **Feature Engineering:**
   - Utilized one-hot encoding on the 'location' column to convert categorical data into a numerical format.

3. **Model Building:**
   - Employed a Linear Regression model as a baseline.
   - Utilized K-Fold cross-validation to measure the model's accuracy.

4. **Model Selection:**
   - Explored various models, including Decision Tree and Lasso, using Grid Search CV to find the optimal parameters.
   - Achieved the best accuracy with the Linear Regression model.

5. **Model Export:**
   - Finalized the Linear Regression model and exported it to a pickle file for easy deployment.

6. **Web Interface:**
   - Created a web interface for clients using HTML, CSS, and JavaScript.
   - Users can input relevant details, and the model predicts the house price accordingly.

## Files and Directory Structure

- `Bengaluru_House_Data.csv`: Kaggle dataset used for training and testing the model.
- `Module 1.ipynb`: Jupyter Notebook containing the code for data cleaning, preprocessing, and model training.
- `client/`: Directory containing the web interface files (HTML, CSS, JavaScript).
- `banglore_home_price_pred_model.pickle`: Pickle file containing the trained Linear Regression model.

## Dependencies

- Python 3.11
- Pandas
- NumPy
- Scikit-learn
- Flask (for the web interface)

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/NikhilAdvani/Bangalore-House-Price-Prediction.git
   cd Bangalore-House-Price-Prediction


Acknowledgments
Special thanks to Codebasics Channel on Youtube for carefully explaining the project.
Thanks to Kaggle for providing the dataset.
Thanks to the open-source community for valuable insights and inspiration.
