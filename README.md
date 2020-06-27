# Chatbot-using-NLTK-in-Python

This example will help us to think through the design and challenge of creating a chatbot. This chatbot answers the questions related to Machine learning.
It is a simple bot with hardly any cognitive skills. Though 'GOD' responds to user input.

Screenshots:

![chat 1 updated](https://user-images.githubusercontent.com/61036755/85920034-e891f300-b88d-11ea-8086-80ad8d6e30e0.png)

![chat data min updated](https://user-images.githubusercontent.com/61036755/85920037-e9c32000-b88d-11ea-9f35-76007486ad1a.png)

![chat 3 all](https://user-images.githubusercontent.com/61036755/85920039-eb8ce380-b88d-11ea-8462-351bef898199.png)


NLTK: NLTK(Natural Language Toolkit) is a leading platform for building Python programs to work with human language data. It provides easy-to-use interfaces to over 50 corpora and lexical resources such as WordNet, along with a suite of text processing libraries for classification, tokenization, stemming, tagging, parsing, and semantic reasoning, wrappers for industrial-strength NLP libraries.
NLTK has been called “a wonderful tool for teaching and working in, computational linguistics using Python,” and “an amazing library to play with natural language.”

Downloading and installing NLTK

Install NLTK: run pip install nltk

Test installation: run python then type import nltk

For platform-specific instructions, read here.
Installing NLTK Packages
import NLTK and run nltk.download().This will open the NLTK downloader from where you can choose the corpora and models to download. You can also download all packages at once.

Text Pre- Processing with NLTK:
The main issue with text data is that it is all in text format (strings). However, Machine learning algorithms need some sort of numerical feature vector in order to perform the task. So before we start with any NLP project we need to pre-process it to make it ideal for work. Basic text pre-processing includes:
Converting the entire text into uppercase or lowercase, so that the algorithm does not treat the same words in different cases as different.

Tokenization: Tokenization is just the term used to describe the process of converting the normal text strings into a list of tokens i.e words that we actually want. Sentence tokenizer can be used to find the list of sentences and Word tokenizer can be used to find the list of words in strings.
The NLTK data package includes a pre-trained Punkt tokenizer for English.
Removing Noise i.e everything that isn’t in a standard number or letter.
Removing Stop words. Sometimes, some extremely common words which would appear to be of little value in helping select documents matching a user need are excluded from the vocabulary entirely. These words are called stop words.

Stemming: Stemming is the process of reducing inflected (or sometimes derived) words to their stem, base or root form — generally a written word form. Example if we were to stem the following words: “Stems”, “Stemming”, “Stemmed”, “and Stemtization”, the result would be a single word “stem”.

Lemmatization: A slight variant of stemming is lemmatization. The major difference between these is, that, stemming can often create non-existent words, whereas lemmas are actual words. So, your root stem, meaning the word you end up with, is not something you can just look up in a dictionary, but you can look up a lemma. Examples of Lemmatization are that “run” is a base form for words like “running” or “ran” or that the word “better” and “good” are in the same lemma so they are considered the same.

TF-IDF Approach:
A problem with the Bag of Words approach is that highly frequent words start to dominate in the document (e.g. larger score), but may not contain as much “informational content”. Also, it will give more weight to longer documents than shorter documents.
One approach is to rescale the frequency of words by how often they appear in all documents so that the scores for frequent words like “the” that are also frequent across all documents are penalized. This approach to scoring is called Term Frequency-Inverse Document Frequency, or TF-IDF for short, where:
Term Frequency: is a scoring of the frequency of the word in the current document.

If you like this repo, please don't forget to ⭐.




