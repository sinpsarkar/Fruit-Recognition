**Fruit-Recognition**

**Project Description:**

In this project, we shall train some pre-defined model architectures like **ResNet50**, **EfficientNetB3** and **InceptionV3** on a large number of Training dataset consisting of images of various fruits.
We shall then use the best model (model with the best accuracy) to predict random images of fruits.

The Observations of the training are as below:

**ResNet50 V2:**

   ![ResNet50](https://user-images.githubusercontent.com/45538409/162629435-424ac38f-ecf1-4f80-aad7-154ca23df281.PNG)

**Inception V3:**

   ![InceptionV3](https://user-images.githubusercontent.com/45538409/162629446-bc4ca6ca-b6d3-475d-9323-451ac397792a.PNG)

**EfficientNet B3**

   ![EfficientNet](https://user-images.githubusercontent.com/45538409/162629451-22c6146c-160b-4bbd-b07b-45d5adce43c2.PNG)

**Observations and Best Model Selection: **
 As we observe above, Efficient Net has the best accuracy and precision for the same epochs and batch size. So, we shall save this model and use it to predict on random/ new images of fruits.
 
 **Improving the Model: **
 
 Here, we have trained the full model for only 1 epoch. We shall try this with 2 or 3 epochs and then compare if the model accuracy and precision is improved. However, we shall be careful not to increase the epochs to a very high number, as that would lead to overfitting issue.

**NOTE : ** As we are using the free GPUs available with Google Colab, Kaggle, Paperspace Gradient, which have a limitation on usage, we are not able to train these architectures for the best possible outcomes.
