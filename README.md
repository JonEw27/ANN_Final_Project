This is our final project for our Artificial Neural Networks and Deep Learning Project. The model has the ability to classify images of disposable drink containers in the Pant A,B,C classes of the Danish bottle redemption system. Currently, with the available data, it does this at about a 77-83% accuracy. 

We used Tensorflow for model definition and training, Keras for building the sequential models, ImageDataGenerator to load images and preprocess, and ModelCheckpoint/EarlyStopping callbacks to save the best model and avoid overfitting.

Some features that we implemented are:
- Customizable input image size and number of classes
- Two convolution + max‐pooling blocks, followed by dense layers with dropout
- Realtime image augmentation on the training set
- Automatic checkpointing of best‐performing model weights
- Detailed evaluation including confusion matrix and per‐class precision/recall/F1

With the provided Google Drive Folder, you can navigate to it with its file path and input that path into the code so that the model will run correctly.

ImageGenerator helped us to rescale the pixel values, augment the training images, and flow images in random batches from the directory. 
