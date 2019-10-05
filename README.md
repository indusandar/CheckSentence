
## Installing
# on windows
pip install -r requirement.txt
# on linux
pip3 install -r requirement.txt


## Training


```
usage: main.py    [--mode 'train']
                  [--ModelPath 'Model']
                  [--linesToTrain 10000]
                  [--data_sent_path './data_all.csv']
                  [--data_answer_path './taskA_answers_all.csv']
                  [--epochs 3]
                  
## Estimating


```
usage: main.py    [--mode 'estimate']
                  [--data_sent_path './data_all.csv']
                  [--data_output './']
                  [--n_lines 200]
                  

## predicting


```
usage: main.py    [--mode 'predict']
                  [--sentence 'He drinks milk']
                  

## get Accracy


```
usage: main.py    [--mode 'getAcc']

