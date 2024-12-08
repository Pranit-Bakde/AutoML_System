## AutoML_System
This project is a fully interactive AutoML Application built using Python and Tkinter, designed to simplify the machine learning process. The application provides a clean graphical interface for users to load datasets, preprocess data, and train machine learning models. Whether you are a beginner or an advanced user, this tool streamlines data analysis, model selection, and evaluation.
# Key Features
# 1. Dataset Import:
Supports CSV and Excel files for seamless data import.
# 2. Automated Data Preprocessing:
Handles missing values by filling them with mean values (numerical columns).
Encodes categorical variables using Label Encoding for compatibility with ML algorithms.
# 3. Intelligent Model Selection:
Automatically identifies the problem type:
Classification: Logistic Regression, Random Forest Classifier.
Regression: Linear Regression, Random Forest Regressor.
# 4. Model Evaluation:
For classification: Measures performance using Accuracy Score.
For regression: Measures performance using Mean Squared Error (MSE).
# 5. Code Generator:
Automatically generates Python code for training and testing the best model.
Reuse or modify the code for other projects.
# 6. Result Visualization:
Generates a Confusion Matrix for classification tasks.
Creates an Actual vs Predicted Scatter Plot for regression tasks.
# 7. Clipboard Integration:
Allows users to copy the generated code directly to the clipboard.

# Installation and Setup
1. Clone or download the repository.
2. Install the required Python libraries:
pip install pandas numpy matplotlib seaborn sklearn pyperclip
3. Run the application using:
python automl_app.py

# Usage Guide
# 1. Step 1: Import Dataset
Click on "Import Dataset" and select a CSV or Excel file.
The dataset will be loaded into the application.
# 2. Step 2: Start Analysis
Select the Target Variable (Dependent) and Independent Variables from your dataset.
The application will preprocess the data and automatically train machine learning models.
# 3. Step 3: View Results
The best model will be displayed along with its performance metrics.
Visualizations like Confusion Matrix or Scatter Plot will be generated based on the problem type.
# 4. Step 4: Copy Generated Code
Click on "Copy Generated Code" to copy the machine learning code to your clipboard.
This code can be reused for other datasets or further customized.
# 5. Step 5: Quit Application
Exit the application by clicking on "Quit".

# How It Works
1. Dataset Handling:

Automatically detects the file type and loads it into a Pandas DataFrame.
Displays dataset information for verification.

2. Data Preprocessing:

Handles missing data by filling numeric columns with mean values.
Encodes string (categorical) data using Label Encoding.

3. Model Training:

Splits the data into training (75%) and testing (25%) sets.
For Classification: Trains Logistic Regression and Random Forest Classifier.
For Regression: Trains Linear Regression and Random Forest Regressor.

4. Best Model Selection:
Evaluates each model using appropriate metrics (accuracy or MSE).
Automatically selects the best-performing model.

5. Visualization:
Classification: Generates a Confusion Matrix heatmap.
Regression: Generates an Actual vs Predicted Scatter Plot.

6. Code Generation:
Produces Python code for training and testing the selected model, making it easy to replicate or extend the results.

# Outputs
# Classification Example:
Confusion Matrix

# Regression Example:
Actual vs Predicted Scatter Plot


# Future Enhancements

Add hyperparameter tuning for better model optimization.
Support for more algorithms like Gradient Boosting, SVM, etc.
Integrate advanced visualizations using libraries like Plotly.
Allow exporting models and results directly as files.


This project is ideal for anyone looking to simplify the machine learning workflow while learning key concepts. Feel free to contribute or suggest improvements!
Happy Coding!
