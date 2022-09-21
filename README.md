# Sentiment-Analysis-from-Images-Using-Deep-Learning

- Training dataset was collected from https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer

- Testing dataset were randomly downloaded from internet and its attached with this repository. 

- Convolutional Neural Network (CNN) was trained to predict 5 different emotions from images. 

- 10 different models with different settings were trained to find the best model 

- The best model was able to predict 5 emotions from images with 88% training accuracy and 70% testing accuracy.

- MobilenetV2 and VGG-19 pre-trained models were used for transfer learning. 

To find the best model, training of models was also done with out using any pre-trained models as images in training dataset were of 48x48 pixels and in pre-trained models inputs were of 224x224 size. Due to this reason, it could effect the accuracy of models with using pre-trained models. The images in the training dataset were not re-sized to make it compatible with pre-trained model as it could also affect the accuracy of the model. Hence it was anticipated that these pre-trained models might not be good match for the given dataset that’s why half of the models were structured without using pre-trained model
