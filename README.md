# language-translation  

**Language Translation using seq2seq RNNs**  

**Summary**   
Translated new sentences from English to French using encoder/decoder techniques, validation accuracy = 0.96  
  
Please see detail in python [notebook](./dlnd_language_translation.ipynb) (.ipynb)  
  
**Sample Results:**  
Epoch   0 Batch  100/538 - Train Accuracy: 0.5422, Validation Accuracy: 0.5650, Loss: 0.8389  
Epoch   0 Batch  200/538 - Train Accuracy: 0.6602, Validation Accuracy: 0.6458, Loss: 0.4918  
Epoch   0 Batch  300/538 - Train Accuracy: 0.7329, Validation Accuracy: 0.7370, Loss: 0.3136  
Epoch   0 Batch  400/538 - Train Accuracy: 0.7785, Validation Accuracy: 0.8079, Loss: 0.1961  
Epoch   0 Batch  500/538 - Train Accuracy: 0.8912, Validation Accuracy: 0.8718, Loss: 0.1019  
Epoch   1 Batch  100/538 - Train Accuracy: 0.9152, Validation Accuracy: 0.8883, Loss: 0.0649  
Epoch   1 Batch  200/538 - Train Accuracy: 0.9150, Validation Accuracy: 0.9219, Loss: 0.0547  
Epoch   1 Batch  300/538 - Train Accuracy: 0.9280, Validation Accuracy: 0.9229, Loss: 0.0505  
Epoch   1 Batch  400/538 - Train Accuracy: 0.9351, Validation Accuracy: 0.9174, Loss: 0.0470  
Epoch   1 Batch  500/538 - Train Accuracy: 0.9506, Validation Accuracy: 0.9309, Loss: 0.0340  
Epoch   2 Batch  100/538 - Train Accuracy: 0.9547, Validation Accuracy: 0.9299, Loss: 0.0320  
Epoch   2 Batch  200/538 - Train Accuracy: 0.9613, Validation Accuracy: 0.9513, Loss: 0.0313  
Epoch   2 Batch  300/538 - Train Accuracy: 0.9501, Validation Accuracy: 0.9403, Loss: 0.0346  
Epoch   2 Batch  400/538 - Train Accuracy: 0.9557, Validation Accuracy: 0.9379, Loss: 0.0348  
Epoch   2 Batch  500/538 - Train Accuracy: 0.9778, Validation Accuracy: 0.9423, Loss: 0.0223  
Epoch   3 Batch  100/538 - Train Accuracy: 0.9574, Validation Accuracy: 0.9489, Loss: 0.0258  
Epoch   3 Batch  200/538 - Train Accuracy: 0.9600, Validation Accuracy: 0.9522, Loss: 0.0257  
Epoch   3 Batch  300/538 - Train Accuracy: 0.9550, Validation Accuracy: 0.9435, Loss: 0.0312  
Epoch   3 Batch  400/538 - Train Accuracy: 0.9468, Validation Accuracy: 0.9458, Loss: 0.0311  
Epoch   3 Batch  500/538 - Train Accuracy: 0.9801, Validation Accuracy: 0.9444, Loss: 0.0196  
Epoch   4 Batch  100/538 - Train Accuracy: 0.9572, Validation Accuracy: 0.9560, Loss: 0.0224  
Epoch   4 Batch  200/538 - Train Accuracy: 0.9658, Validation Accuracy: 0.9441, Loss: 0.0231  
Epoch   4 Batch  300/538 - Train Accuracy: 0.9673, Validation Accuracy: 0.9537, Loss: 0.0247  
Epoch   4 Batch  400/538 - Train Accuracy: 0.9548, Validation Accuracy: 0.9517, Loss: 0.0281  
Epoch   4 Batch  500/538 - Train Accuracy: 0.9748, Validation Accuracy: 0.9627, Loss: 0.0176  
```
INFO:tensorflow:Restoring parameters from checkpoints/dev
Input
  Word Ids:      [120, 13, 141, 55, 198, 12, 66]
  English Words: ['he', 'saw', 'a', 'old', 'yellow', 'truck', '.']

Prediction
  Word Ids:      [142, 58, 241, 230, 253, 92, 339, 290, 1]
  French Words: il a vu un vieux camion jaune . <EOS>
```
