# REDfold
Residual Encoder-Decoder Network for RNA Secondary Structure Prediction. This repository contains the source code for REDfold from the paper "REDfold: Accurate RNA Secondary Structure Prediction using Residual Encoder-Decoder Network". Please cite the paper if you use our source code or data.

## Usage
The users are welcome to use REDfold webserver available at https://redfold.ee.ncyu.edu.tw for RNA structure prediction.
REDfold is implemented in Python code and the cross-platform compatible program can be installed through the [wheel package](https://redfold.ee.ncyu.edu.tw).
It can predict the RNA secondary structure based on the RNA sequences.

### System Requirement
 python (>=3.7)  
 biopython (>=1.79)  
 numpy (>=1.21)  
 pandas(>=1.3.5)  
 scipy (>=1.7.3)  
 torch (>=1.9+cu111) 

### Installation
REDfold can be installed through the [wheel package](https://redfold.ee.ncyu.edu.tw).
```
% pip install redfold-1.14a0-py2.py3-none-any.whl
```

### Test data
REDfold can predict the RNA secondary structure with fasta-formatted RNA sequences.
```
% redfold directory_containing_fasta_files
>D00002586
GCUCGCGUGGCGUAAUGGCAACGCGUCUGACUUCUAAUCAGAAGAUUAUGGGUUCGACCCCCAUCGUGAGUG
(((((((..((((.......)))).(((((.......))))).....(((((.......)))))))))))).
```


### Train model
REDfold can train the parameters with BPSEQ-formatted RNA sequences.
```
% redfold -train directory_containing_bpseq_files
```

## Web Server
REDfold web server is available at https://redfold.ee.ncyu.edu.tw

## Reference
Chen, Chun-Chi, and Yi-Ming Chan. "REDfold: Accurate RNA Secondary Structure Prediction using Residual Encoder-Decoder Network." BMC Bioinformatics (2023).

