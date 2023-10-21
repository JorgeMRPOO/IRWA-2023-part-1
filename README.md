# IRWA-2023-part-1

This project is about Ukraine-Russian war tweets during 2022. With python3 programming language and some libraries we pre-process a text with tweets to a structured processing data with tweet information. This data will be analyze to find interesting results.

At the beginning, we imported all the libraries required for the task. Then, we’ve loaded the two documents needed (in the variable “path”, you have to add your own link where you have these documents). 

In the function called build_terms(), we’ve preprocessed the text applying some criteria. First of all, transforming to lowercase and removing the dots so .war can be interpreted as war. Then, text is split into words (tokenization). We remove stop words using ntlk and stem terms to make it easier to search for words. Finally, we prune the hashtag from the words in the tweet text. Then, we return the processed tweet in a structured dataframe. 

Hashtags (#) are removed because they are stored in the column name “Hashtags” and it’s not necessary to keep them. 
