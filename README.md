# Neural Machine Translation
![th (1)](https://user-images.githubusercontent.com/68260816/197610234-b072b036-1616-42e9-b459-5329fd69391e.jpg)


In this project, we will build a neural machine translation system using modern techniques for sequence-to-sequence modeling. 
We will first implement a baseline encoder-decoder architecture, then improve upon the baseline by adding an attention mechanism and implementing beam search. 
The end result will be a fully functional translation system capable of <strong>translating simple German sentences into English.</strong>


## Setup

First we install and import the required dependencies. These include:
* `torch` for modeling and training
* `torchtext` for data collection
* `sentencepiece` for subword tokenization
* `sacrebleu` for BLEU score evaluation
