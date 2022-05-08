# CS598-DL4HealthCare
## Introduction
In our group project, our target aims to reproduce the proposed deep learning approaches in Zhang's work including re-implementing bidirectional LSTM-CRF model, in terms of simultaneously identifying 5 types of clinical entities from Chinese EHR data. In our project, we followed Zhang's work to set up 5 types of clinical entities including: symptom (S), test (T), body part (B), treatment (Tr) and diagnosis (D).
## Dependencies
In the project root directory, run the following to install the required packages.
```
pip3 install -r requirements.txt
```
## Data download instruction
We already uploaded the data we used in our project.
## Preprocessing
We uploaded jupyter notebook file **'LSTM-CRF.ipynb'**, you could run the cells in order and get the preprocessed data. The preprocessing work is consist of tagging, building vocab dictionary and building index map.
## Training
In the jupyter notebook file **'LSTM-CRF.ipynb'**, training work will be completed after run the cell **Model training and saving**
## Evaluation
In the jupyter notebook file **'LSTM-CRF.ipynb'**, after training work you will get train_output files. And **analysis (new).ipynb** is used to evaluate the performance of the model.
## Results
![alt text](https://github.com/woshicqy/CS598-DL4HealthCare/blob/main/data/table1.JPG?raw=true "Title")
![alt text](https://github.com/woshicqy/CS598-DL4HealthCare/blob/main/data/table2.JPG?raw=true "Title")
## Reference
https://medinform.jmir.org/2018/4/e50/
