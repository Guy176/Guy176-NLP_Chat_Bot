#In this project I decided to use the following intents:
#book_flight
#change_flight
#cancel_flight
#If the intent of user wasn’t one of those three, I have classified the intent as ‘unknown’ from the user
#These are the states I used: 0 : start 1 : book_flight 2 : change_flight 3 : cancel_flight 4 : flight_destination 5 : change_destination 6 : reason for cancellation 7 : flight dates
#I HAVE NOT RETURNED POLARITY SEPARATELY ON PURPOSE BECAUSE SENTIMENT ANALYSIS INCLUDES POLARITY SCORE IN IT I used the TFIDF for feature extraction and Random Forest Classifier for classification I used the en_core_Ib_sm spacy model and used #the SpacyTextBlob pipeline to recognize the sentiment which includes the polarity from the user input
