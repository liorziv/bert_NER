# BERT NER (Entity Recognition)

In the project I issued BERT ner task, implementing fine tuning on pre-train BERT

The collab document is at 

[ [https://colab.research.google.com/drive/1rB--0v7SwczbZlTPLdTpJPc0J6-g-c2N?usp=sharing](https://colab.research.google.com/drive/1rB--0v7SwczbZlTPLdTpJPc0J6-g-c2N?usp=sharing)](https://www.notion.so/https-colab-research-google-com-drive-1rB-0v7SwczbZlTPLdTpJPc0J6-g-c2N-usp-sharing-a4fbb081297d43118ff7b01b94b0f8c3)

The code cotains the next stages:
1. Preprocess your data for training:
    - extract sentences and their labels
    - added additional embadding to each word as part of a sentence
    - tokenize each sentence
    - using wordpiece to decode the tokens
2. Convert data to tensors and load tensors into DataLoaders
3.Initialize your pre-trained BERT and set the hyperparameters (BertForTokenClassification with the BERT paper authors’ recommended hyperparameters)
4.Train and validate

refrences -

[https://www.depends-on-the-definition.com/named-entity-recognition-with-bert/](https://www.depends-on-the-definition.com/named-entity-recognition-with-bert/)[https://gab41.lab41.org/how-to-fine-tune-bert-for-named-entity-recognition-2257b5e5ce7](https://gab41.lab41.org/how-to-fine-tune-bert-for-named-entity-recognition-2257b5e5ce7)