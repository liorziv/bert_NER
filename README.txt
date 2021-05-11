In this projet i tried to implement Bert Ner implementing fine tunnig on pre-train bert

The collab document is at - https://colab.research.google.com/drive/1rB--0v7SwczbZlTPLdTpJPc0J6-g-c2N?usp=sharing

The code cotians the next stages:
1.Preprocess your data for training:
	- extract sentences and their labels
	- added additional embdding to each word as part of a sentence
	- tokenize each sentence
	- using wordpiece to decode the tokens
2.Convert data to tensors and load tensors into DataLoaders
3.Initialize your pre-trained bert and set the hyperparameters (I used BertForTokenClassification with the BERT paper authors’ recommended hyperparameters)
4.Train and validate 



refrences - 

https://www.depends-on-the-definition.com/named-entity-recognition-with-bert/
https://gab41.lab41.org/how-to-fine-tune-bert-for-named-entity-recognition-2257b5e5ce7