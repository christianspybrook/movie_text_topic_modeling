movie_test_topic_modeling
=========================

Topic Modeling Project
----------------------

The goal of this project is to build, optimize, and contrast different methods of topic modeling for the task of grouping movies by their respective genres, based on the texts of the movies' taglines.

 The Scikit Learn, SpaCy and Gensim libraries will be used to implement this project.

 I will begin by constructing a dataset from real movie data, obtained through API requests from the TMDb website. The data will consist of the taglines and genre categories of each movie. I will build both a Latent Dirichlet Allocation (LDA) model and a Non-negative Matrix Factorization (NMF) model, for comparison. Consideration will be given to building other models, such as an Ida2vec network, if the results are not sufficient.

 Project Workflow:

1. [build_dataset_nb](https://github.com/christianspybrook/movie_text_topic_modeling/tree/master/build_dataset)
: Notebook containing the code I used to assemble the movie tagline text data.
2. [lda_model_nb](https://github.com/christianspybrook/movie_text_topic_modeling/blob/master/topic_models/lda_models/lda_model.ipynb)
: Notebook containing the code I used to build an LDA model, using Scikit Learn and SpaCy.

 In Progress...
 	updated as required. 
