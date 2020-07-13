# Pneumonia Xray Detection

## This model can detect if there is some abnormality in chest Xray from Xray Image.

The dataset used for training and validation is taken from Kaggle.
Dataset link : [Chest X-ray image](https://www.kaggle.com/muzin11/chest-xray-image)

# Here a Convolutional Neural Network is used to recognize face mask.
## A convolutional neural network is one of the main categories to do images recognition, images classifications. Objects detections recognize faces, etc., are some of the areas where CNNs are widely used. In this model, there are 4 convolution layer followed boy max-pooling layer and in each layer. Stride: 1 Padding: valid activation : Relu

After 4 convolution layer, there is a flatten layer then there is 2 fully connected dense layer. Activation :Relu

In the output layer as there is two output as it is a binary classification and activation is sigmoid.

# Summary of Model:

![Summary of Model](https://github.com/rakib1521/Pneumonia_Xray_Detection/blob/master/Model/Pneumonia_Xray_Detection_model.png)


# Detail of Model:

![Detail of Model](https://github.com/rakib1521/Pneumonia_Xray_Detection/blob/master/Model/Pneumonia_Xray_Detection_model_detail.PNG)

# Training and validation accuracy:
![accuracy](https://github.com/rakib1521/Pneumonia_Xray_Detection/blob/master/Photos/Pneumonia_Xray_Detection_accuracy.png)

# Training and validation loss:
![loss](https://github.com/rakib1521/Pneumonia_Xray_Detection/blob/master/Photos/Pneumonia_Xray_Detection_loss.png)

# output:
  ![result](https://github.com/rakib1521/Pneumonia_Xray_Detection/blob/master/Photos/Pneumonia_Xray_Detection_result.PNG)
