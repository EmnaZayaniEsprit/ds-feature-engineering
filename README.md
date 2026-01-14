# Feature Engineering

In supervised machine learning and statistical modeling, Feature Engineering is a preprocessing step which transforms raw data into
features that more precisely represent the underlying problem for a predictive model. This is often achieved by means of applying domain knowledge to data. Before jumping to the notebooks, please read the machine [learning workflow file](machine_learning_workflow.md)

## Contents

### 1. Notebook [***1.1_intro_to_fe***](1.1_intro_to_fe.ipynb) 
It covers the basics of feature engineering, with hands-on example from a given dataset, explaining various techniques like
+ `Imputation`
+ `Categorical Encoding`
+ `Feature Scaling`
+ `Feature Expansion` 
### 2. Notebook [***2.1_advanced_fe***](2.1_advanced_fe.ipynb) 
It is dedicated to various advanced technologies used in a Machine Learning workflow, namely 
+ `ColumnTransformer`
+ `Pipeline`


### 3. Notebook [***1.2_intro_to_fe_exercise***](1.2_intro_to_fe_exercise.ipynb) 
In this exercise you transform raw data in a way that is suitable to be used for modeling
+ `Imputation`
+ `Categorical Encoding`
+ `Feature Scaling`
+ `Discretization`

### 4. Notebook [***2.2_advanced_fe***](2.2_advanced_fe_exercise.ipynb)
This exercise is built on top the other and you will transform raw data using also
+ `ColumnTransformer`
+ `Pipeline`

## Set up your Environment

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute the notebooks.

### **`macOS`** type the following commands : 

- Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
    ```
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```


*Note: If there are errors during environment setup, try removing the versions from the failing packages in the requirements file.*

