# Text_NER

Name Entity Recognition

In this project, a customized tokenizer is trained using the clean CNN news CSV file data and then train a NER model with loading pretrained BERT-base-cased model weights.

The tokens that are not among recognized entities are labeld with -100 (O).

The words that are broken to multiple subwords after get tokenized, the sunwords are labeled as -100 and only the first part is cllasified.




