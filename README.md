## Projects
### Blood-Cell Image Classification
![Histogram of Oriented Gradient Feature Extraction By Class](/imgs/hog_example.png)
*Visualizing feature extraction for histogram of oriented gradients by blood cell class.*


Ideated and implemented an image processing pipeline in **Python** to extract novel feature vectors and perform dimensionality reduction for images of healthy blood cells. Built, optimized, and compared performance of a combination of simple and deep learning classification models using **TensorFlow** functional API. The simplest and lowest cost logistic regression model achieved an 82% test accuracy, while the highest performing neural network achieved a 94% test accuracy. The high performance of both the simple and complex models indicate that the extracted features are highly descriptive and sufficiently unique between classes. Additionaly, while extraction of complex features using convolutional nerual networks aids in improving accuracy of blood cell image classification, simpler features, like luminance histograms and histogram of oriented gradients, are highly descriptive and far less computationally expensive to extract. Follow the link for an in depth review of [methods and findings.](blood_cell_classification.pdf)





