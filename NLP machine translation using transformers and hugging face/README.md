# Machine Translation with Transformers

## DEPENDENCIES:
This code has been written using **Python 3.7**
* torch == 1.5.0
* einops == 0.2.0
* tqdm == 4.46.1
* transformers == 2.11.0
* numpy


## INPUT DATA:

Preparing the input data is very simple. Suppose you are going to train a
 machine translation system to translate from English to French,
 you need two text files, one for English and the other for French. 
Each of these files have on every line a sentence from English in the file corresponding to English and the corresponding sentence from French in the file corresponding to French. You need to have two of these pairs, one for training and the other for validation.

Check the structure of the files in the `data/raw/en` and the `data/raw/fr` folders that contains sample text files if you want to use them. 


Play around with the code to understand how to train a machine translation model by fine tuning the `nn.Transformer` model 
in PyTorch and also using HuggingFace.

