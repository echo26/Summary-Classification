# Summary-Classification

This project classify student summary in speech into an original text that each student summarized.
I used Python, NLTK, RegEx and Naive Bayes.

From 3 different articles of text file, chunked noun phrases using RegEx and NLTK. Then, made a bag of noun phrases.

Then, made a prediction using Naive Bayes. It will judge each noun phrase's original articles. Fortunately, the topic of articles are not similar, I got 99% accuracy. Also, I made a vector for each aritcles with regarding all noun phrases as features.

Then, I will process students speech that summarized one of the articles above. As these speechs have some onomatopoeias, I need to remove them with stop words.

I chunked each summary using RegEx and NLTK into nouns like the above and make the vector for each noun. Then, I compared it with the articles vector using cosine similarity. Then, I classified summary to the closest article.



