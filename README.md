# Steps to run
- ./preprocessing_caml/my_dataproc.ipynb : run this to create raw data that combines discharge notes and medical encoding label in the same row, and create train, validation, test split 
- ./Explainable-Automated-Medical-Coding-master: main code for the model
in embeddings/ folder: run the code in playground.ipynb to create Word2Vec model for word and code embedding
in HLAN/HAN_train.py : main training script. We use VSCode to launch training, see ./vscode/launch.json for hyperparameters and settings

# Data 
Since data is quite large, we are not submitting data folders with this repo
The post processing data should be put in /Explainable-Automated-Medical-Coding-master/datasets/data
The Word2Vec embedding model should be put in //Explainable-Automated-Medical-Coding-master/embeddings
