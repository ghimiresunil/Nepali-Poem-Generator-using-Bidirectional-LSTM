# Nepali-Poem-Generator-using-Bidirectional-LSTM
Nepali Poem Generator using Bidirectional LSTM

## Generating Sequence of N-gram Tokens:

Language modelling requires a sequence input data, as given a sequence (of words/tokens) the aim is the predict next word/token.

The next step is Tokenization. Tokenization is a process of extracting tokens (terms / words) from a corpus. Python’s library Keras has inbuilt model for tokenization which can be used to obtain the tokens and their index in the corpus. After this step, every text document in the dataset is converted into sequence of tokens.

Lets take a look at one of the input Sequence: 

[[1337, 2623],<br>
 [1337, 2623, 12],<br>
 [1337, 2623, 12, 39],<br>
 [1337, 2623, 12, 39, 103]]

In the above output [1337, 2623], [1337, 2623, 12], [1337, 2623, 12, 39] and so on represents the ngram phrases generated from the input data, where every integer corresponds to the index of a particular word in the complete vocabulary of words present in the text. For example <br>

### Line: नछाडी जानोस् हे मेरा प्राण
### Ngrams: | Sequence of Tokens
