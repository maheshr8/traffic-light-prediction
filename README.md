# traffic-light-prediction

Dataset is from following link:
https://www.kaggle.com/datasets/mbornoe/lisa-traffic-light-dataset

Abstract:
The traffic light recognition project aims to create deep-learning neural network models utilizing the LISA Traffic Light dataset available on Kaggle, which can identify traffic lights in images. LISA is an acronym for "Learning from Imbalanced and Structured Aspects". The motivation behind this work is to develop accurate and efficient models that can be used in autonomous driving systems to detect traffic lights and enhance safety on the roads. The project utilized 9053 traffic light images from the total dataset captured in both daytime and nighttime, which were split into a training set (80%) and a testing set (20%). Two different state-of-the-art object detection models, Faster R-CNN and Single Shot MultiBox Detector (SSD), were trained on this dataset to detect traffic lights. Pre-trained neural networks from TensorFlow object detection were used for training. The data was prepared using TensorFlow object detection API scripts, and the models’ performance was evaluated using mean Average Precision (mAP) and Recall. After 150,000 training steps, the Faster R-CNN model achieved an mAP of 27.4% and a recall of 13.44%, while the SSD model achieved an mAP of 30.97% and a recall of 14.31%. Overall, this project demonstrates the effectiveness of using deep neural networks for traffic light recognition.

