# Music-Recommendation-System
This repository contains mainly two approaches for recommending songs to a user.
1. Using distributed item representations, with the data being that of various sessions of various users, recommendation of the song is made to the user based on his last sessions.
2. Using word embedding, based on the songs the user is listening to, suggestions are made from the songs most similar to those songs.

There are datasets also available along with the relevant folders.
In order to run the code on your system, the following steps have to be followed:
1. Clone the repository
2. Unzip the dataset files.
3. Change the path in the code and set it to the path of the file in your system.

The packages required for the project are:
1. gensim
2. scipy
3. tensorflow

If you have these installed, you are good to go.

The file structure of the project is as follows:
1. dir_over_sequence - implementation of distributed item representations over the session activities of the user  
	a. sessions.zip (dataset)  
	b. prod2vec_over_sessions.ipynb
2. word_embedding_on_songmetatdata - implementation of word embedding over song details to find similarity  
	a. song_data.csv.zip (song metadata)  
	b. kaggle_visible_evaluation_triplets.zip (user triplets)  
	c. word2vec_over_song_metadata.ipynb

