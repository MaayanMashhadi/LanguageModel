# LanguageModel

Language modeling is the task of predicting the next word in a sequence of words.
In this project, I used the IMDB dataset, preprocessed the text, built a vocabulary, and trained a language model.

Tasks:

Organized the IMDB dataset to fit a language modeling (LM) task by formatting each sample as a sequence of words for next-word prediction.

Split the dataset into training, validation, and test sets to enable proper model evaluation and prevent overfitting.

Used the TreebankWordTokenizer from NLTK to tokenize the raw text into sequences of tokens suitable for language modeling.

Created a vocabulary from the training data, mapping each unique token to a numerical index.

Defined a custom Dataset class along with a DataLoader to efficiently load and batch the tokenized data during training.

Defined a language model using a recurrent neural network.
