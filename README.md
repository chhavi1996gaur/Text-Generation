# Text-Generation

The objective of this project is to make a Text Generation model for the task of generating News Headlines.
The project begins with importing the dataset and then cleaning of the data. Here I read the headlines from all the files and read them as one file.
Here I removed the stop words and punctuations fro, the news headlines and then converted them
into tokens.
After that I generated a sequence of the tokens and then did the padding of all the sequences to make the sequences of similar lengths.
After that I used the Embedding layers to perform the Text Generation.
