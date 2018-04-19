# Names Entity Recognition from Online News

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
