# Diabetes Prediction Project

This project focuses on building a machine learning model to predict diabetes based on a dataset. 

## Project Steps

1. **Data Preparation:**
   - Downloaded and extracted a diabetes dataset. 
   - Loaded the dataset into a Pandas DataFrame. 
   - Analyzed the data using descriptive statistics (e.g., `.describe()`, `.info()`). 
   - Checked for missing values. 

2. **Exploratory Data Analysis (EDA):**
   - Visualized the distribution of key features using bar plots, histograms, and line plots. 
   - Investigated relationships between features and the target variable (diabetes) by creating plots like: 
     - Diabetes by Gender
     - Diabetes by Age
     - Diabetes by Location
     - Diabetes by Race
     - Correlation matrix for numerical features
   - Created a new feature `Risk_Factor_Count` based on factors like hypertension, heart disease, and smoking history. 

3. **Feature Engineering and Data Cleaning:**
   - Converted necessary features to numerical data types for model training. 
   - Handled missing values by removing rows with missing values in key features. 
   - Created an `age_group` feature for better visualization and modeling. 
   - Visualized feature interactions using scatter plots and box plots.
   - A 3D scatter plot was generated to display relationships between age, BMI, and blood glucose level.

4. **Model Training:**
   - Converted categorical features to numerical using OneHotEncoder.
   - Split the dataset into training and testing sets using `train_test_split`. 
   - Standardized numerical features using StandardScaler. 
   - Trained and evaluated various classification models including:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - Support Vector Machine
     - K-Nearest Neighbors
   - Evaluated models based on metrics like accuracy, precision, recall, F1-score, and ROC-AUC.
   - Identified the best-performing model. 

5. **Model Saving and Usage:**
   - Saved the best model using Pickle.
   - Demonstrated how to load and use the saved model to make predictions.

## Future Work

- Experiment with different feature engineering techniques to improve model performance.
- Optimize hyperparameters for the chosen model. 
- Consider using ensemble methods or other advanced machine learning algorithms.
- Deploy the model for real-time diabetes predictions. 


## Libraries Used

- zipfile
- numpy
- pandas
- matplotlib
- seaborn
- sklearn (for model training, preprocessing, evaluation)
- pickle (for model saving/loading)


