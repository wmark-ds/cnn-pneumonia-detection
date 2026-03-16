### Detecting Pneumonia in X-Rays using CNN, with Grad-CAM XAI


A group project with Avan Salman.


This repository features an implementation of a CNN for detecting Pneumonia in X-rays, using the Kaggle dataset: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia



- Using this Kaggle project as a baseline: https://www.kaggle.com/code/madz2000/pneumonia-detection-using-cnn-92-6-accuracy
- We aimed to improve the model achitecture and implemented hyperparameter optimization using the Optuna package.
- We also implemented Grad-CAM XAI technique. We used this guide to help implementation: https://keras.io/examples/vision/grad_cam/
- For Grad-CAM we implemented both normal and guided Grad-CAM.




![guided grad-cam](guided_grad_cam.png)
![false_negative](false_negatives.png)
![false positives](false_positives.png)