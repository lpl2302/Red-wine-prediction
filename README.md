# Red-wine-prediction
This project focuses on predicting the quality of red wine based on various physicochemical properties using a simple linear regression model. The dataset used for this analysis comes from a wine quality dataset that contains multiple features related to the composition of wine.

**Dataset:** https://archive.ics.uci.edu/dataset/186/wine+quality

## Introduction
This project focuses on predicting the quality of red wine based on various physicochemical properties using a simple linear regression model. The dataset used for this analysis comes from a wine quality dataset that contains multiple features related to the composition of wine. This project is done as a practice for simple linear regression in the Machine learning with Python by IBM on Coursera.

### a) Requirements
The project requires the following Python libraries, which can be installed using the provided commands:

- pandas: For data manipulation and analysis.
- matplotlib: For creating visualizations.
- scikit-learn: For applying machine learning algorithms, specifically linear regression.

### b) Dataset

The dataset (winequality-red.csv) contains the following columns:
- fixed acidity
- volatile acidity
- citric acid
- residual sugar
- chlorides
- free sulfur dioxide
- total sulfur dioxide
- density
- pH
- sulphates
- alcohol
- quality: (Target variable)

## II. Usage

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:

  ```bash
  jupyter notebook main.ipynb
  ```

4. Run all the cells in the notebook to:
   
- Load the wine quality dataset.
- Preprocess the data.
- Train the simple linear regression model.
- Evaluate the model performance.

5. To test the model with your own data, modify the appropriate cell in the notebook:
   
- Create a Pandas DataFrame with the features (fixed acidity, volatile acidity, etc.) and input the values.
- Run the prediction using the trained model:

  ```bash
  model.predict([[fixed_acidity, volatile_acidity, citric_acid, ..., alcohol]])
  ```

This will output the predicted wine quality based on your input data.

## III. Citations

- Dataset: Cortez, P., Cerdeira, A., Almeida, F., Matos, T., & Reis, J. (2009). Wine Quality [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C56S3T.
- Learning and practicing: https://www.coursera.org/learn/machine-learning-with-python
