# Character-RNN

In this repository is a Jupyter Notebook that has sample code to construct a character-level Long Short Term Memory (LSTM) utilizing PyTorch.  This file can be accessed here [Character_Level_RNN_Solution.ipynb](https://github.com/the-john/Character-RNN/blob/master/Character_Level_RNN_Solution.ipynb).  

What this model does is train, character by character on some text.  In this code, the text is the book [Anna Karenina](https://github.com/the-john/Character-RNN/blob/master/data/anna.txt).  Then the model will generate new text charcter by charater that "sounds like" text from the book.

This network is based off of Andrej Karpathy's [post on RNNs](http://karpathy.github.io/2015/05/21/rnn-effectiveness/), and implimented in [Torch](https://github.com/karpathy/char-rnn).

In the sample code you have:
- Loading the data
- Tokenization of the data
- Data pre-processing
- Making mini-batches for training
- Defining the Model
- Training the Model
- Instantiating the Model
- Setting hyperparameters
- Testing the model
- Priming and Generating new text

All of this code is done in Python 3.x
