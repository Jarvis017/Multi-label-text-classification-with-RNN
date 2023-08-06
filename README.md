# Multi-label-text-classification-with-RNN
using RNN architecture(GRU, LSTM, etc.) for Multi Label Classification on Persian Sentences  

# About the project

The purpose of the project was calculate the similarity between two pair sentences and also finding the subject of two sentences.

Process of the project:
* Use [Hazm](https://github.com/roshan-research/hazm) library for parsing and extracting subjects
* Prepare sentences for feeding into model
* Create multiple LSTM and GRU models with Keras

## Dataset

The dataset consist of 3 columns. 2 columns are the sentences and the third one is the similarity score.

All of the subject of the sentences should be in one of 6 specified classes. The classes are as follows:
* Boy/Man
* Girl/Woman
* Child
* Animal
* Others(like people)
* Unkown

After finding subject, every pair-sentences were assigned to their own classes.

link of Dataset:

https://github.com/Ledengary/COPER/blob/main/Datasets/PerSICK.csv
