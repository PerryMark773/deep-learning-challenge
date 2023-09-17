# Alphabet Soup Deep Learning Challenge

## Background
The nonprofit foundation Alphabet Soup requires a tool that can aid in selecting applicants that are most likely to succeed in their ventures when funded. The objective of this challenge is to harness the power of machine learning and neural networks to create a binary classifier. This classifier will predict whether an applicant will be successful when funded by Alphabet Soup based on various features.

### Dataset
The dataset provided comprises over 34,000 organizations that have received funding from Alphabet Soup over the years. The dataset has the following columns:
- **EIN and NAME**: Identification columns
- **APPLICATION_TYPE**: Alphabet Soup application type
- **AFFILIATION**: Affiliated sector of industry
- **CLASSIFICATION**: Government organization classification
- **USE_CASE**: Use case for funding
- **ORGANIZATION**: Organization type
- **STATUS**: Active status
- **INCOME_AMT**: Income classification
- **SPECIAL_CONSIDERATIONS**: Special considerations for the application
- **ASK_AMT**: Funding amount requested
- **IS_SUCCESSFUL**: Was the money used effectively

## Instructions

### Step 1: Preprocess the Data
- Upload the starter file to Google Colab.
- Read in the `charity_data.csv` to a Pandas DataFrame.
  - Target Variable: `IS_SUCCESSFUL`
  - Features: All columns except `EIN`, `NAME`, and `IS_SUCCESSFUL`.
- Drop the `EIN` and `NAME` columns.
- Encode categorical variables.
- Split the data into training and testing datasets.
- Scale the datasets.

### Step 2: Compile, Train, and Evaluate the Model
- Create a neural network model using TensorFlow and Keras.
  - The model underwent multiple iterations with different numbers of Dense layers, including models with 3 and 4 layers.
- Compile and train the model.
- Evaluate the model to determine its loss and accuracy.

### Step 3: Optimize the Model
- Implement various methods to optimize the model with the goal of achieving a predictive accuracy higher than 75%.
  - Methods included adjusting the data, adding more neurons, and modifying activation functions.
- Save the optimized model results.

### Step 4: Report on the Neural Network Model
- Write a comprehensive report detailing the model's performance, including data preprocessing, model training, and optimization details.

### Step 5: Upload Files to the Repository
- Download the Google Colab notebooks and push them to the GitHub repository.

## Requirements
Detailed in the instructions, addressing each preprocessing step, model creation, training, evaluation, optimization, and report writing.
