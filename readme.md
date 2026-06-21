# What is this project?

This projects extracts and then clusters financial knowledge through the use of Graph databases.

# What is the code base able to do?

The code base is seperated into **three** seperate modules:
- __Extractor__: This module extracts webs content from Investopedia and Wikipedia asynchronously
- __Database Persistor__: This module preprocess the text using NLP techniques and then extracts nodes and relationship from the text to be inserted into the graph database
- __Clustering__: Cluster nodes basde on semantic closeness