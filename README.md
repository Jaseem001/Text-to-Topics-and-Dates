# Text-to-Topics-and-Dates
This is a simple python script that takes in a text as input and outputs the main topics discussed in the text along with the dates which can be passed to Google Calendar API, for example.

## Finding Topics
I used gensim for preprocessing the data and to find the keywords from the given text.

## Finding Dates
This program uses the built in python dateparser to parse preprocessed text. Usually dateparser wont work that well for human generated text, but the text has been preprocessed in such a manner that it is easy for the dateparser to identify dates. For example, a lot of common English words referring to dates will be replaced to its respective datetime value.
