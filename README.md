# Prediction-Model-for-Student-Placement-and-Graduation

## Project Overview

This project involves the development of predictive models for:
1. **Student Placement Prediction**: Predicting whether a student will secure a placement based on their academic records and other relevant features.
2. **Forecasting Graduation Year**: Estimating the year of graduation for students based on their college details and academic progress.

## Contents

- **datasets.zip**: Contains CSV files used for training and testing the models.
- **notebooks.ipynb**: Includes Jupyter notebook with the code for both prediction and forecasting tasks.
- **output.zip**: Contains the CSV files with the model's predictions and forecasted graduation years.
- **requirements.txt**: Lists the Python packages required to run the notebooks.
- **LICENSE**: MIT License for this project.
- **.gitignore**: Specifies files and directories to be ignored by Git.

## Installation

To set up the environment for running the notebooks, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone <repository_url>
   cd <repository_directory>

2. **Create a Virtual Environment**
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. **Install Dependencies**
   ```
   pip install -r requirements.txt

## Usage
Data Preparation: Extract the contents of datasets.zip into a directory.

Run Notebooks: Extract the contents of notebooks.zip and open the Jupyter notebooks in your preferred environment (e.g., Jupyter Notebook or JupyterLab).

Model Execution:
    The notebook.ipynb script predicts the graduation year based on student details and whether a student will secure a placement.

Output: The predictions will be saved in the output.zip file. Extract this file to review the results.

## File Description
datasets.zip: Contains the CSV files 01 Train Data.csv, 02 Test Data.csv, and others for training and testing.
notebook.ipynb: Includes graduation year and placement status code for model training and prediction.
output.zip: Contains placement_predictions.csv and predicted_graduation_year.csv files with the results from the models.

## Acknowledgements
Tools Used: Visual Studio Code, Jupyter Notebooks, Python libraries (e.g., Scikit-learn)
