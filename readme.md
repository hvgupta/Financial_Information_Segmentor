# What is this project?

This projects extracts and then clusters financial knowledge through the use of Graph databases.

# What is the code base able to do?

The code base is separated into **three** seperate modules:
- __Extractor__: This module extracts web content from Investopedia and Wikipedia asynchronously
- __Database Persistor__: This module preprocesses the text using NLP techniques and then extracts nodes and relationships from the text to be inserted into the graph database
- __Clustering__: Cluster nodes based on semantic closeness