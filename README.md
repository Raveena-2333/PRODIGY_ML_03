1. **Data Preparation**: Images of cats and dogs from a Kaggle dataset are used for training the model.

2. **Feature Extraction**: Features are extracted from the images using the VGG16 model, a pre-trained convolutional neural network (CNN) known for its effectiveness in image classification tasks.

3. **Model Training**: An SVM classifier is trained on the extracted features to learn the patterns distinguishing between cat and dog images.

4. **Evaluation**: The trained model is evaluated on a separate test set to assess its performance, achieving an accuracy of 95.65%.

5. **Prediction**: After training, the model can predict whether an uploaded image is of a cat or a dog by extracting features from the VGG16 model and using the SVM classifier.

6. **Result**: The model correctly predicts the classes of the uploaded images as either cat or dog.

Overall, the SVM classifier, coupled with features extracted from the VGG16 model, effectively distinguishes between images of cats and dogs with high accuracy.

**Dataset link :-** https://www.kaggle.com/c/dogs-vs-cats/data
