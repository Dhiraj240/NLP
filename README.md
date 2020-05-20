# Problem Approach

**The problem of making cluster and sentence matching was divided into three parts:**

1.	**Data Cleaning :** The first part of the project was to make sure that sentences don’t have unnecessary data. 

Since, text is the most unstructured form of all the available data, various types of noise are present in it and the data is not readily analyzable without any pre-processing. The entire process of cleaning and standardization of text, making it noise-free and ready for analysis is known as text preprocessing.

It is predominantly comprised of three steps:
●	Noise Removal
●	Lexicon Normalization
●	Object Standardization


2.	**Sentence matching algorithm :** In this part of the project we tried to devise a model which would give the percentage similarity of the two given sentence. 

A number of text matching techniques are available depending   upon the requirement like Levenshtein Distance, Phonetic Matching, Flexible String Matching, Cosine Similarity

3.	**Increasing Computation speed :** Since there will be 200 to 300 sentences and it will take around 200000 comparison and each comparison would take around 0.5 millisecond. So, instead of computing serially one by one we implemented it parallely using distributed systems to increase the speed of computation.
