# Transformer architecture from scratch in Python using pytorch

## Overview : 

This repository contains the implementation of the Transformer architecture inspired from the 'Attention is All You Need Paper' from scratch using the pytorch library. This model was trained on the Game of Thrones screenplay dataset with the corpus containing total of 50000 words, for the task of next word prediction.

## Model Details :

* Corpus size : 50000 words(tokens)
* Final loss : 1.73
* Total epochs : 70
* Learning Rate : 0.005
* Optimizer : Adam
* Loss Function : Cross Entropy
* Total Prameters : 25.1 Million

## Model results after tranining : 

![alt text](./Screenshot%202025-03-30%20141355.png)


### Note : 

Although the result is good enough, still there's a room for improvement. We can optimize the accuracy by adding dropout layers, reducing the number of total parameters to avoid overfitting or by implementing the kv cache for efficient use of hardware and much more. May be I will do it later, but for now it's good enough.

# Thanks!!
