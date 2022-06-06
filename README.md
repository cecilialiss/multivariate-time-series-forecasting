# multivariate-time-series-forecasting

============LIBRARY DEPENDENCIES==========
pandas 		1.4.1
numpy 		1.12.2
matplotlib 		3.5.1 
pytorch		1.10.2
sklearn		1.0.2

===========FILES==========================
The datasets used are:
- weather_features.csv
- energy_dataset.csv

They contain raw data for the weather and energy usage. After data cleaning, the data are splitted into 70% training, 10% validation and 20% test sets.
test_data.csv contains the test set from the datasets above.

All the codes used for this project can be found in MLP_vs_RNN_aggregated_BACKUP.ipynb

the .pth files are the saved best trained MLP and RNN models for easier testing.

============INSTRUCTIONS==================
To reproduce the results on test set, run all the cells in Part 5 in the Jupyter notebook.
