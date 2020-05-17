# Overview for to create a Simple ChatBot from scratch
Import necessary libraries
Downloading and installing NLTK
Reading in the corpus( Here I'm using the Wikipedia page for chatbots as our corpus. Copy the contents from the page and place it in a text file named ‘chatbot.txt’. However, you can use any corpus of your choice)
## Next step, Need to convert all text into Machine readable language:
 Converting the entire text into uppercase or lowercase
Tokenization
Removing Noise 
Stop words
Stemming,Lemmatization(This is Normalisation)
Keyword matching(we shall define a function for a greeting by the bot i.e if a user’s input is a greeting, the bot shall return a greeting response.ELIZA uses a simple keyword matching for greetings. We will utilize the same concept here)
Bag of Words
# TF-IDF Approach
Term Frequency: is a scoring of the frequency of the word in the current document.

TF = (Number of times term t appears in a document)/(Number of terms in the document)
Inverse Document Frequency: is a scoring of how rare the word is across documents.

IDF = 1+log(N/n), where, N is the number of documents and n is the number of documents a term t has appeared in.
# Cosine Similarity
Tf-idf weight is a weight often used in information retrieval and text mining. This weight is a statistical measure used to evaluate how important a word is to a document in a collection or corpus.
To generate a response from our bot for input questions, the concept of document similarity will be used. We define a function response which searches the user’s utterance for one or more known keywords and returns one of several possible responses. If it doesn’t find the input matching any of the keywords, it returns a response:” I am sorry! I don’t understand you”
# Finally the basic chatbot is ready :)
 we will feed the lines that we want our bot to say while starting and ending a conversation depending upon user’s input.
