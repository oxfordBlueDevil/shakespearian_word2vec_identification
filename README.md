# Shakespearian Word2Vec Identification

We employ a series of unsupervised learning algorithms to uncover the writings of a modern author mixed with the writings of Shakespeare. Our corpus consists of scattered pages of the complete works of Shakespeare in combination of random pages of the works of another, very modern author. We first created word embeddings for our corpus, and then apply t-stochastic neighbor embedding to project the word embeddings onto a two-dimensional space. We then apply k-means clustering to identify which pages (documents) in our corpus are written by Shakespeare.
