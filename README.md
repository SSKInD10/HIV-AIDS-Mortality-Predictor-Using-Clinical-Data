HIV AIDS Mortality Predictor Using Clinical Trial Data

Dataset obtained from https://archive.ics.uci.edu/dataset/890/aids+clinical+trials+group+study+175. Few errors manually added in dataset to enable preprocessing to be performed.

Main Objective is to preprocess the dataset, build and tune multiple ML models to predict mortality based on clinical data.

Jupyter Notebook code.ipynb for above present in JupyterNotebook subdirectory with a copy of the dataset and other artefacts generated during preprocessing dataset and building ML models.

A Simple WebApp was created using Streamlit and hosted on Streamlit Cloud to deploy the ML models for prediction.

WebApp URL is https://hiv-dataset-classifcation-h5lr2aashssdzbgk6auczz.streamlit.app/

Code for deployment is present in DeploymentCode subdirectory. Main app script is app.py and script for performing preprocessing of the dataset is preprocess.py

Simple WebApp Enables user to input a single record or a csv file with multiple records for performing predictions. The user may use any of the 6 models trained and made available. Also, few sample visualization graphs like feature importance, distance of input sample from train dataset records are available for user to chose a model best suited for their need.

Deployment Code is also available at https://github.com/kowboykoushik/hiv-dataset-classifcation/blob/main/app.py
