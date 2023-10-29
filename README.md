# IRWA-2023-part-2

This is a repository to upload projects of the subject Information Retrieval & Web Analytics.

This project is about Ukraine-Russian war tweets during 2022. With python3 programming language and some libraries we pre-process a text with tweets to a structured processing data with tweet information. This data will be analyze to find interesting results.

After we have preprocessed the text and we have the tweets structured, we create the inverted index, the search() function for the queries, and then the TF-IDF Ranking. With this, we obtain a ranking of documents sorted by relevance.
The results of this can be seen in the notebook “Indexing_Part.ipynb”. In the last part, we display the ten most “predicted relevant” documents for each of the queries.

For those queries, we have computed the rank of the documents with the TF-IDF algorithm, and then merged the results with the “Evaluation_gt.csv” file, so we can do the evaluation. For each of the queries, we get a dataframe with 10 relevant documents and 30 that are not relevant (10 not relevant for the query and 20 relevant for the other ones). Then we analysis with different evaluation metrics used in information retrieval and recommendation systems to measure the effectiveness of a model in retrieving relevant items from a list of recommendations.

Authors: Abril Masgrau Turró, Jorge Martínez Rosa and Enric Riba Sáez.

University Pompeu Fabra.
