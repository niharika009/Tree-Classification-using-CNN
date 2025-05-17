# Tree-Classification-using-CNN

Problem Statement
The objective of this project is to develop a deep learning model capable of accurately classifying
images of tree leaves into 30 distinct tree species. This tool aims to assist botanists, environmental
researchers, and educators in plant identification tasks.


Project Overview
This project addresses a multi-class image classification challenge, where the goal is to categorize
images of tree leaves using a Convolutional Neural Network (CNN). To enhance performance and
reduce training time, we employ MobileNetV2, a pre-trained model available in TensorFlow&#39;s
applications library.
Key Features:
 Transfer Learning: Leveraged MobileNetV2 for feature extraction.
 Custom Classification Layers: Added dense layers tailored for our 30-class problem.
 Data Augmentation: Implemented techniques like rotation, zoom, and flipping to improve
generalization.
 Performance Visualization: Utilized accuracy/loss plots and a confusion matrix to assess
model performance.
 User-Friendly Prediction: Developed a simple function to predict tree species from input
images.
Dataset Information
 Dataset Name: Tree Species Identification Dataset
 Source: Kaggle Dataset
 Structure: Contains 1,600 images divided into training and validation sets, each organized
into 30 class-specific folders.
 Image Specifications: All images are resized to 128x128 pixels and normalized prior to
model ingestion.
Sample Tree Classes:
amla, asopalav, babul, bamboo, banyan, bili, cactus, champa, coconut, garmalo, gulmohor, gunda,
jamun, kanchan, kesudo, khajur, mango, motichanoti, neem, nilgiri, other, pilikaren, pipal,
saptaparni, shirish, simlo, sitafal, sonmahor, sugarcane, vad
Technologies Used
 Programming Language: Python
 Libraries: TensorFlow, Keras, NumPy, Matplotlib, Seaborn
 Model Architecture: MobileNetV2 (Transfer Learning)


Results
 Training Accuracy: 98.75%
 Validation Accuracy: 94.06%
 The model demonstrates strong generalization capabilities with minimal overfitting.
Performance evaluation includes:
 Accuracy and Loss Curves: To monitor training progress.
 Confusion Matrix: To visualize class-wise prediction accuracy.
