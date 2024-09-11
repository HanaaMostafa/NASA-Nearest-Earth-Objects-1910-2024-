# Readme

The provided code performs a machine learning task focused on classifying Near-Earth Objects (NEOs) as hazardous or non-hazardous based on features such as absolute magnitude and relative velocity. Here is a brief summary of what the code accomplishes:

1. **Data Importing and Cleaning:**
   - Imports a dataset containing information about NEOs from a CSV file.
   - Removes missing values from the dataset to ensure data quality.
   - Displays the first few rows of the cleaned dataset to understand its structure.

2. **Exploratory Data Analysis (EDA):**
   - Conducts EDA using visualization libraries like Matplotlib and Seaborn.
   - Explores data distribution and correlations using pairplot and countplot.
   - Creates a correlation heatmap to visualize feature correlations.

3. **Preprocessing and Model Training:**
   - Selects specific features and encodes categorical variables.
   - Normalizes numerical features using StandardScaler.
   - Handles imbalanced classes by oversampling the minority class.
   - Splits the data into training and testing sets.
   - Trains a Random Forest Classifier on the training data.

4. **Evaluation Metrics:**
   - Evaluates the trained model by calculating metrics like precision, recall, F1-score, and AUC-ROC.
   - Prints a classification report and the calculated metric values for model evaluation.

5. **Conclusion:**
   - The code demonstrates the process of training a machine learning model to classify NEOs as hazardous or non-hazardous based on given features.
   - It showcases the evaluation of the model's performance using standard classification metrics.

In summary, the code pipeline involves data preprocessing (including missing values removal), exploratory analysis, model training, and evaluation to classify NEOs based on their features and determine their hazardousness.
