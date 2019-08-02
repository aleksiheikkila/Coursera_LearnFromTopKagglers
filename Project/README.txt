Further instructions on the notebook (KaggleProj_Final.ipynb)

    - KaggleProj_Final.ipynb is the all-encompassing jupyter notebook
    - DATA_FOLDER variable in the notebook points the folder where one should put
        - the original data files provided on Kaggle (not included in the zip)
        - the pickle files in the zip
    - The python_relevant_module_versions.txt just lists the dependencies
    - by default the submission files are being written to the present working directotry (usually the dir where the notebook is located)


I did not include the data_all_v4.msgpack file that contains the feature engineered dataset.
This is due to its size.
However, the notebook contains the code to re-create it (takes some time though).

The final serialized model lies in '2019-03-16-model-xgb.pickle'
It generated (after the LB probe adjustment) FINAL_SUBMISSION.csv