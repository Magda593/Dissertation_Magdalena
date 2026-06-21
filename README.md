# Dissertation_Magdalena

Worked over the CIC-IDS2017 dataset, firstly by analyzing each file by then and at the end connecting all of them in a singular pandas dataframe. 
I verified six different models and compared them based on the main evaluation metrics: f1 score, recall and accuracy. 

To ensure reproducibility and keep dependencies isolated, in my project i utilized a Python virtual environment (.venv). The scripts and Jupyter Notebooks run inside a dedicated custom kernel linked to this environment.

Create the Virtual Environment:
    python -m venv .venv

I then installed packages one by one: 
    pip install pandas - data manipulation and loading datasets
    pip install numpy - for numerical operations and math
    pip install scikit-learn - machine learning algorithms and preprocessing
    pip install matplotlib - for plotting graphics and visualization
    pip install imbalanced-learn - for using smote on the imbalanced data
    pip install ipykernel - to run my jupyter notebook in vs code
    pip install xgboost and lightgbm - models

To run i had to choose the kernel at the right top of each 

