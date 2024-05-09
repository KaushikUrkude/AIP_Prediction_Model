# Anti-inflammatory Peptide Prediction

## Project Overview
This project aims to predict anti-inflammatory peptides using a machine learning approach. It leverages bioinformatics and machine learning to identify potential anti-inflammatory peptides from protein sequences. The model is trained on known sequences using a RandomForestClassifier and makes predictions on new sequences.

## Datasets
The project utilizes three key datasets:

- **Positive_dataset**: This contains sequences known to have anti-inflammatory properties. These sequences are used to train the model as positive examples.
- **Negative_dataset**: This includes sequences confirmed not to have anti-inflammatory properties. They serve as negative examples in the model training process.
- **Candidate_dataset**: Comprises sequences for which anti-inflammatory properties are unknown. The model predicts the potential of these sequences to be anti-inflammatory.

- Usage
Open the Jupyter Notebook
Launch Jupyter Notebook or JupyterLab in the project directory:
bash - jupyter notebook
bash-jupyter lab
1.Run the Notebook
2.Open the Fresh_final_123456.ipynb notebook and execute the cells sequentially to:
    Read and process the sequence data from Positive_dataset and Negative_dataset.
    Extract features using biopython and propy.
    Train the RandomForest model using 5-fold cross-validation.
    Predict anti-inflammatory potential on the Candidate_dataset.
3.Predict New Data
    Modify the paths to your new sequence data in the notebook to predict their anti-inflammatory potential.
