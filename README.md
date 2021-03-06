# Project Report :
## Hand Gesture Recognition using Convolutional Neural Networks
* In this mini-project, I've trained a ConvNet on a dataset [(Link)](https://www.kaggle.com/gti-upm/leapgestrecog) to correctly identify 10 different types of hand gestures (shown below).

![Hand Gestures](./misc/hand_gestures.png)

* The ConvNet model architecture used for training is illustrated below : 

![ConvNet Architecture](./misc/model1_convnet.png)

* The dataset of 20000 examples was split into 16000 training examples (80%) and 4000 test examples (20%).
* Evaluation Metric used for determining model accuracy - Accuracy Score
* Model Training Info. :
   * Model Loss Curve :
        
      ![Loss Curve](./misc/model_loss_curve.png)

   * Model Accuracy Curve :
    
      ![Accuracy Curve](./misc/model_accuracy_curve.png)

* Model Performance Details :
    * Confusion Matrix (The row indices are the actual labels & the column names are the predicted labels) :
    
      ![Confusion Matrix](./misc/confusion_matrix_cnn.png)

    * Final Epoch (Epoch 10) Training Details :
    
        loss : 1.5578e-04 | accuracy : 1.0000 | val_loss : 5.3446e-04 | val_accuracy : 0.9998
    * Training Set Accuracy Score : 100%
    * Test Set Accuracy Score : 99.98%
#### Results :
For the trained **ConvNet** model, we've obtained an in-sample accuracy score of 100% and an **out-of-sample accuracy score of 99.98%** .
