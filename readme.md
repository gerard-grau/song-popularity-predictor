## Instructions on how to execute and reproduce our results

1. Download the dataset from this [kaggle repository](https://www.kaggle.com/datasets/jarredpriester/taylor-swift-spotify-dataset).

2. Extract the zip file and save it in the same directory as the notebooks.

3. Make sure that you have Python 3.x installed. You can check your Python version by running `python --version` in your terminal.

4. Install the necessary Python libraries. You can do this by running `pip install pandas scikit-learn` in your terminal.

5. Execute the preprocessing Jupyter notebook. This will save the train-test split in your current directory as CSV files. The command to run the notebook is `jupyter notebook preprocessing.ipynb`.

6. Execute the modelling Jupyter notebook. This notebook requires the files generated in the previous step. The command to run the notebook is `jupyter notebook modelling.ipynb`.