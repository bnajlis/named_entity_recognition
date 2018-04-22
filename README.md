# Online News Named Entity Recognition

This project aimed to create a series of models for the extraction of Named Entities (People, Locations, Organizations, Dates) from news headlines obtained online. We created two models: a traditional Natural Processing Language Model using Maximum Entropy, and a Deep Neural Network Model using pre-trained word embeddings. Accuracy results of both models show similar performance, but the requirements and limitations of both models are different and can help determine what type of model is best suited for specific use cases. 

This project was completed as part of the DS8008 Natural Language Processing Course at the Masters in Data Science Program at Ryerson University in Toronto, Ontario during the months of January through April 2018. 

## Named Entity Extraction
* Subtask of Information Extraction that seeks to locate and classify named entities in text into pre-defined categories: persons, organizations, locations”
    Definition Source: Wikipedia - https://en.wikipedia.org/wiki/Named-entity_recognition
* Extracts information out of unstructured data (news articles, emails, blog posts, scientific papers)

* Similar to Part-of-Speech tagging: instead of looking for POS we are looking for entities

* Not so similar to Part-of-Speech tagging: an entity can span multiple words (i.e.: Terry Fox, Rogers Communications, South Korea)

## Problem Definition

* Research has shown that NER systems developed for a specific domain do not perform well against other domains. 

* Named Entities are open word class problem: Basic NER models rely on list of entities (gazetteer) to identify them, such list can be expensive to maintain. 

* Considerable effort is required in training NER for new domains.

* State of art NER systems rely heavily on hand crafted features that works only on certain languages.

* Our Goal: Develop machine learning models that predict named entities without any of the above. Compare models performance.
