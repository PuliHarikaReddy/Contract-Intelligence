# Contract-Intelligence
Contract analysis is a process used to examine and track information within a contract.
This trackable information could be financial or related to the status of the contract, its clauses, and changes in company policy
Contract analysis starts to become even more powerful when the analysis can be extended to multiple contracts
Organizations analyze their contracts to improve their strategy, risk management and also their contracting process.
For example, “How many of their contracts contain Force Majeure clause? Who are the liable parties involved? “ And many

## Named Entity Recognition
- Named-entity recognition (NER) is the process of automatically identifying the entities discussed in a text
- It is probably the first step towards information extraction that seeks to locate and classify named entities in text into pre-defined categories such as the names of persons, organizations, locations, expressions of times, quantities, monetary values, percentages, etc.
- NER is used in many fields of Natural Language Processing.

## spaCy
- spaCy is an open-source library for advanced Natural Language Processing in Python.
- spaCy uses neural network models for parsing, tagging & entity recognition
- The spaCy allows you to train NER models by both updating an existing spacy model to suit the specific context of your text documents and also to train a fresh NER model from scratch. 
- It can be used to build information extraction or natural language understanding systems, or to preprocess text for deep learning.
- Pre-trained entities - ‘person’, ‘organization’, ‘location’ 
- Instead of using a existing pre-trained spacy model and update it, we are creating an empty model
- Entities extracted using NER are Liability of the parties involved, Notice Type and Termination Period

## BERT
- BERT stands for Bidirectional Encoder Representations from Transformers.
- It is designed to pre-train deep bidirectional representations from unlabeled text by jointly conditioning on both left and right context.
- A BERT model is already pre-trained on a large corpus of unlabeled text which includes the entire Wikipedia(that’s 2,500 million words!) and Book Corpus (800 million words).
- This is the reason behind the success of BERT, because the model is trained on such huge corpus, it starts to pick up deeper meanings and understands how the language works.







