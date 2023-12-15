# NLP_project2023
My NLP project on developing a cosine similarity checker and movie genre classifier

Task 1: Getting a cosine similarity of two sets of words.
Models used: Word2Vec(method b) BERT embeddings(method c)
Some of the words are OOV(Out Of Vocabulary)
The golden values are the similarity ranked by humans.
The value of the golden value is the average of the human values.


Task 2: Classifying the movie genre into nine categories.
Models used: BiLSTM(method b)   BERT(method c)
Some of the categories have a small number of training data. --> This has been dealt with by fine-tuning the threshold binary value of each label(9 genres)


This project is built on Google Colab using T4 GPU.

# Warning
The pipeline takes over 4 hours to run on T4 GPU.
