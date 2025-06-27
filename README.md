In this week I've loaded the images using tools like image_dataset_from_directory.I have visualised the sample images from each class.
Then understanding the properties of images like dimensions,class labels.Then after steped into the data preperation here I did resize the image and rescaled the images.
Then model selection has been done by verifying the transfer learning model and pre-trained weights.Then after model training and model tuning has been done by Tune hyperparameters: learning rate, batch size, 
number of layers, dropout rate.then I used callbacks toEarlyStopping: To stop training when validation performance stops improving. Trained the model using .fit() with appropriate epochs,
batch_size, and callbacks like EarlyStopping.Model Performance Visualization: Accuracy & Loss Trends.Then model evaluation done by ysing metrics like confusion matrix,classifictaion report.
With the help of confusion matrix then we can come to know how many images are detected by the model on diagonal that is the size of detected images .
