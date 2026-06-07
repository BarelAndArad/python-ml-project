# Instructions for running predictive modeling and model serialization code

# Prerequisites
    Ensure the following files are available in your working directory:
        ''' dataset.csv ''' (The clean dataset created from previous parts)
        ''' pkl.random_forest_B&A ''' (The serialized best model file)
        ''' pkl.elastic_net_model ''' (best elastic net model file for competition)


    Open Jupyter Lab or Jupyter Notebook environment:
        Install the next Libraries from the following code if necessary: 
        # pip install pandas numpy matplotlib seaborn textblob scikit-learn

       

# Environment Setup 
    This part is for uploading the essential data science, NLP, and machine learning libraries.
    The libraries and specific modules imported in this section are:
        * pandas (as pd)
        * numpy (as np)
        * matplotlib.pyplot (as plt)
        * seaborn (as sns)
        * textblob (TextBlob)
        * ast
        * re
        * pickle
        * sklearn.model_selection (train_test_split, GridSearchCV)
        * sklearn.compose (ColumnTransformer)
        * sklearn.pipeline (Pipeline)
        * sklearn.impute (SimpleImputer)
        * sklearn.preprocessing (StandardScaler, OneHotEncoder)
        * sklearn.linear_model (ElasticNet)
        * sklearn.ensemble (RandomForestRegressor)
        * sklearn.metrics (r2_score, mean_squared_error, mean_absolute_error)

    Place 'dataset.csv' in the same folder as the notebook before running
 * Run its cells as they are.

        
## Libraries and Python Versions
        Python Kernel: 3.11.5
        pandas==2.0.3
        numpy==1.24.3
        matplotlib==3.7.2
        seaborn==0.12.2
        textblob==0.20.0
        scikit-learn==1.3.0
    


#   Data Loading & Preprocessing Functions
    This part loads the dataset and defines all custom functions for cleaning text fields, extracting text sentiment and handling missing values.
    
    
* Run its cells as they are.


#  Master Data Aggregation & Feature Analysis
      It ensures consistent pipeline execution across the training and testing datasets.
    
* Run its cells as they are.


# Elastic Net Model
    This part runs the whole process of the Elastic Net model. 
    It's running takes few minutes.
    It will show the stats of the checked Cross-Validation, Train, Test and comprasion values.


 * suggestion - Use 'pkl' file from authors GItHub instead of running the model fitting. 
 
 * Run its cells as they are.


# Random Forest Model    
    This part runs the whole process of the Random Forest Model.
    It will show the stats of the checked Cross-Validation, Train, Test and comprasion values.

 * Be Aware! the model fitting running takes Few Hours!
 * suggestion - Use 'pkl' file from authors GItHub instead of running the model fitting. 
    
 * Run its cells as they are.


#  Best Model Exporting as PKL
    This part inside of the selected best model.
    It creates PKL file based on the model details. 
    # This Pkl file is uploaded to GitHub.
 * Note!: If you didn't ran the Random Forest model (used the authors 'pkl' file ) this part won't run. Skip to the next part.
 * Run its cells as they are.

#  Feature Importance 
    This part includes an assistent function and large number of graphs. 
    
 * Run its cells as they are.


#  Predictive Error & Outlier Distribution
    This part includes a large number of graphs and tables.

 * Run its cells as they are.

