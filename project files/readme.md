project executable code description:
The code loads and preprocesses a blood cell dataset for classification.
It applies data augmentation techniques to improve model generalization.
A pre-trained deep learning model (Transfer Learning) is loaded for feature extraction.
Custom layers are added for fine-tuning the classification task.
The model is compiled with categorical cross-entropy loss and an optimizer like Adam.
It trains on the dataset while tracking accuracy and validation loss.
After training, it evaluates the model on test data.
The code generates a confusion matrix and classification report.
It also includes a predict function to classify new blood cell images.
Finally, the trained model is saved for future use.
