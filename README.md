# language-translation  

**Language Translation using seq2seq RNNs**  

**Summary**   
Translated new sentences from English to French using encoder/decoder techniques, validation accuracy = 0.96  
  
Please see detail in python notebook (.ipynb)  
  
**Sample Results:**  
```
INFO:tensorflow:Restoring parameters from checkpoints/dev
Input
  Word Ids:      [120, 13, 141, 55, 198, 12, 66]
  English Words: ['he', 'saw', 'a', 'old', 'yellow', 'truck', '.']

Prediction
  Word Ids:      [142, 58, 241, 230, 253, 92, 339, 290, 1]
  French Words: il a vu un vieux camion jaune . <EOS>
```
