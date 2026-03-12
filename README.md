Here we trying to Train the BERT model to fit to our specific use case. 
Bert is general trained in 2 parts, Masked Language modeling and Next sentence Prediction. 
We clearly split these 2 training parts into individual training modules. And at the end we combined both the training methods adn trained the model.

MASKED LANGUAGE MODELING : MLM in short is used for training the BERT model to predict the next word in the sentence. We train the model by masking about 15% of the words in the text using special token [MASK]
NEXT SENTENCE PREDICTION : Given 2 sentences NSP will be able to say if the sentence 2 is the next sentence of the sentence 1 or not. Training for this is done by randomly ordering about 50% of the sentences. 
