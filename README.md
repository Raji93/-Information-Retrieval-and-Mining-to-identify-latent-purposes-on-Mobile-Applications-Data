# Information-Retrieval-and-Mining-to-identify-latent-purposes-on-Mobile-Applications-Data

This Project aims at discovering the purposes of various mobile applications from the android applications data set.


Step 1:
-------
The data set is loaded as data frames and then converted into documents.

Step 2:
-------
Each app from the data set is created as a seperate document.

Normalization:
--------------
All the stop words are downweighted using TF-IDF normalization.

Topic Discovery:
----------------
Each app is then viewed as a distribution over 20 topics, and each topic is a distribution of over all the permissions in the data using LatentDirichletAllocation class in scikit-learn.

Visualization:
--------------
Using t-SNE,perform document -topic visualization. 
