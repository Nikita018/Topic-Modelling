# Topic-Modelling
Working with unstructured data, extracting insights and building models


### Ideas Explored in Food and Cooking Notebook :
1. Extracted data from web API in JSON format
2. Used python library Beautiful Soup for extracting data from the json file
3. Pulled out all the latest posts and comments on the posts along with the timestamp. Converted original UNIX timestamp to a readable format.
4. Cleaned the data for analysis - Removed punctuations, context specific stop words and unicode characters
5. Performed tokenization and Lemmatization to find root words as per the context
6. Explored Latent Dirichlet Allocation for topic modelling
7. Recorded the three trending topics
8. Found TF-IDF scores for each word in a topic
9. For repeating words in a topic, computed the average TF-IDF score
10. Gave more weightage to the inference of the different topics based on the words having highest TF-IDF scores in a topic




### Ideas Explored in Literature notebook : 
1. Extracted data from web API in JSON format
2. Used python library Beautiful Soup for extracting data from the json file
3. Pulled out all the latest posts and comments on the posts along with the timestamp. Converted original UNIX timestamp to a readable format.
4. Cleaned the data for analysis - Removed punctuations, context specific stop words and unicode characters
5. Performed tokenization and Lemmatization to find root words as per the context. Created the corpus
6. Used TF_IDF vectorizer to convert each document in the corpus into a sparse matrix of TF-IDF features
7. Performed SVD decomposition on the TF-IDF feature matrix
8. Based on the eigen values and the eigen vectors, finding the words/phrases belongind to each topic,
9. Derieving Inferences
