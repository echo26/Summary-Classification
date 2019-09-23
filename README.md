# Summary-Classification

This project classify student summary in speech into an original text that each student summarized.
I used Python, NLTK, RegEx and Naive Bayes.

From 3 different articles of text file, chunked noun phrases using RegEx and NLTK. Then, made a bag of noun phrases.

I made a vector for each articles with all noun phrases as features. Then, I will process students speech to vector that summarized one of the articles above. As these speechs have some onomatopoeias, I need to remove them with stop words.


Then, made a prediction using Cosine Similarity by comparing the vectors. I got 95% accuracy.