# REDfold
Residual Encoder-Decoder Network for RNA Secondary Structure Prediction. This repository contains the source code for REDfold from the paper "REDfold: Accurate RNA Secondary Structure Prediction using Residual Encoder-Decoder Network". Please cite the paper if you use our source code or data.

## Usage
The users are welcome to use REDfold webserver available at https://redfold.ee.ncyu.edu.tw for RNA structure prediction.
REDfold is implemented in Python code and cross-platform compatible.

### Data preprocess
Preprocess the data with BPSEQ-formatted RNA sequences.
python process_data.py --test_files directory_containing_bpseq_files

### Train model
REDfold can train its parameters from preprocessed data.
python test_redfold.py --train 1

### Test data
REDfold test for predicting RNA secondary structure.
python test_redfold.py

# Web Server
Web server is available at https://redfold.ee.ncyu.edu.tw



