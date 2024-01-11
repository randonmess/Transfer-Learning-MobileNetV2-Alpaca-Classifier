# Transfer-Learning-MobileNetV2-Alpaca-Classifier
Using a MobileNetV2 previously trained on ImageNet dataset, an Alpaca Image Classifier is implemented using transfer learning. First, images of Alpacas are augmented to increase the number of examples. The top layer is replaced with binary classification layer and is trained on the dataset for 5 epochs.

## Objective
- Create a dataset from a directory
- Preprocess and augment data using the Sequential API
- Adapt a pretrained model to new data and train a classifier using the Functional API and MobileNet
- Fine-tune a classifier's final layers to improve accuracy

## Results
- With only a trainable top layer, the model returned an accuracy of 83%
- Training the model from layer 120 onwards, the accuracy improved to 97%
