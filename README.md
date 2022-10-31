# Web-Scraping-NLP
The project consists of two components- web scraping and natural language processing.
The web scraping is done on the Amazon product review page using Beautifulsoup library and the relevant information extracted are stored in a csv file.
This csv file is extracted and NLP model is trained on the dataset.The model predicts whether the review given in positive or negative.
The procedure followed is:
-> Web scraping using the BeautifulSoup library.
->Applying various procedures like removal of stopwords, word tokenization, lemmatization.
->Using the glove for word to vector conversion.
->Using the tensorflow library to train the model.
