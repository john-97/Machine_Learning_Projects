# Machine_Learning_Projects
Tensorflow | Personal Projects

### Projects
---
* Image Classification (Shopee Code League)
* Language Translation (DataHack Hackathon)

### Image Classification (Shopee Code League)
---
* Classifying 58693 images into 42 categories, Supervised Learning
* Transfer learning with ResNet50
* Data Augmentation with ImageDataGenerator
* Classification with MaxPooling, GlobalMaxPooling, Dropout, and Softmax
* loss: 6.4463 - accuracy: 42.37095%

### Language Translation (DataHack Hackathon)
---
* Encoder-Decoder-Attention RNN, English to Traditional Chinese translator
* Encoder (English Embeddings, GRU)
* Attention (English -> Attention Weights -> Context Vector)
* Decoder (Context Vector + Chinese Word -> Next Chinese Word)
* Loss (SparseCategoricalCrossEntropy, Adam)
  - Mask all padded sequences - missing word
