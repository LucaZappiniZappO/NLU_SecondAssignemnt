
# NLU Assignment 2 

The notebook starts with reading the file train.txt using the function in conll.py `read_corpus_conll()` then is used for creating the references that will be used later for the evaluation of the NER performances. The lines with `-DOCSTART-` are removed in this phase.

# TASK 1
Token level performaces are obtained after obtaining the predicion in the list `hyps`,note that the function `tag_Mapping` convert spacy entity label into conll format, using the function `token_level_performance(refs,hyps)` that uses the scikit function `classification_report` to create the report for tokens level.
Chunck level performance are evaluated by using the function evaluate of conll.py.

# TASK 2 
The function group_entities takes as input the document and recognized named entities using noun_chunks method of spaCy. 
The evaluation of the frequancy are done separatly by creating a dict for te frequency by counting the number of istances of each type of the entity tipe

# TASK 3
The third task is done in the function  `exstend_entity_span`


