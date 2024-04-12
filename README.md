# Accidents in France

Source of data:

* Kaggle: https://www.kaggle.com/datasets/ahmedlahlou/accidents-in-france-from-2005-to-2016
* Which was probably gathered from a platform collecting open French public data https://www.data.gouv.fr/fr/datasets/bases-de-donnees-annuelles-des-accidents-corporels-de-la-circulation-routiere-annees-de-2005-a-2022/

Contents of files:

* French_accidents.pdf: Documentation
* characteristics.ipynb, places.ipynb, users.ipynb, vehicles.ipynb: Jupyter notebooks for analyzing each corresponding data file
* data_merge.ipynb: Merging the separate files into one dataset and training a Bayes Network.
* visualization.ipynb: Notebook used to generate data for the visualizations on the map
* data/..: Data files (original/raw and preprocessed)
* model_indegree4.xml : Trained bayes network saved in xmlbif format
