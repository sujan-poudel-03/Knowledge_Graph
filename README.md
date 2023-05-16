****Knowledge Graph****
This repository contains the code for extracting entities from news text, building a knowledge graph, and performing question answering based on the graph.

**Scraping Code**
The initial step involved scraping news text from the website https://english.onlinekhabar.com/ using the Beautiful Soup library. The code for web scraping can be found in the Scraping_Code.ipynb file.

**Knowledge Graph Notebook**
The **Knowledge_Graph.ipynb** notebook contains the following steps:

**Step 1:** Preprocessing of Scraped Text

The scraped news text is processed using NLTK and spaCy libraries for tasks such as tokenization, stop word removal, and punctuation removal.

**Step 2:** Entity Extraction

The spaCy model **en_core_web_sm** is used to extract entities like subject, object, and relationship from the preprocessed text.

**Step 3:** Knowledge Graph Construction

The extracted entities are plotted into a directed knowledge graph using the NetworkX library. The resulting graph is saved as a graph database file named **knowledge_graph.graphml**.

**Step 4:** Question Answering

Question answering is performed based on the relationships in the knowledge graph to provide answers related to the entities.

Please note that the code and notebooks provided in this repository serve as an example and can be further customized for specific use cases.

Feel free to explore the code and adapt it to your requirements.

Let me know if you need further assistance or have any questions!




