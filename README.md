# Traffic-Signs-Recognition-using-CNN-and-Keras
Overview
In the era of Artificial Intelligence, this project focuses on Traffic Sign Recognition using Deep Learning, specifically Convolutional Neural Networks (CNN) and the Keras library. The goal is to develop a model capable of classifying traffic signs in images, contributing to the safety of autonomous vehicles.

Deep Learning Model
The project builds a CNN-based model using Keras for the classification of traffic signs into various categories. The dataset comprises over 50,000 images of different traffic signs, including speed limits, crossings, and traffic signals. With 43 different classes, the dataset is diverse, varying in image count for each class.

Dataset
The image dataset is organized into two folders, 'train' and 'test,' containing class-wise images. The dataset is available for download, with a manageable file size of approximately 314.36 MB.

Data Processing
The images and their corresponding labels are stored in lists, converted into a NumPy array for model input. The shape of the data is (39209, 30, 30, 3), representing the number of images, image size (30x30 pixels), and RGB values.

GUI for Traffic Signs Classifier
To enhance user interaction, a graphical user interface (GUI) is implemented. A Python file named 'gui.py' is created, incorporating the trained model ('traffic_classifier.h5'). Users can upload images via the GUI, and the classifier button determines the class of the uploaded image. The classify() function processes the image and predicts the traffic sign class.
