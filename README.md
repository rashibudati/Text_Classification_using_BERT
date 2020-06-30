# Text-Classification-using-BERT
This repository contains the text classification. Categorized the type of company based on the company's description. 

## Software Requirement:

1. Python 3.5+
2. Pytorch 1.5.1+cu101
3. Numpy
4. Matplotlib
5. Transformers
6. Scikit learn

# Note:

1. The file test_output has the tags predicted for the corresponding company description.
2. I have used BERT base-uncased model to train. I split the train dataset into train and validation sets and achived 59% F1 score after training the model for 40 epochs. I froze every layer but the top layer for BERT and added classification layer on top of it.

