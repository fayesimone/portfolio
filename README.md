## Projects
### Blood Cell Classification
![Histogram of Oriented Gradient Feature Extraction By Class](/imgs/hog_example.png)
*Visualizing feature extraction for histogram of oriented gradients by blood cell class.*


Ideated and implemented an image processing pipeline in **Python** to extract novel feature vectors and perform dimensionality reduction for images of healthy blood cells. Built, optimized, and compared performance of a combination of simple and deep learning classification models using **TensorFlow** functional API. The simplest and lowest cost logistic regression model achieved an 82% test accuracy, while the highest performing neural network achieved a 94% test accuracy. The high performance of both the simple and complex models indicate that the extracted features are highly descriptive and sufficiently unique between classes. Additionaly, while extraction of complex features using convolutional nerual networks aids in improving accuracy of blood cell image classification, simpler features, like luminance histograms and histogram of oriented gradients, are highly descriptive and far less computationally expensive to extract. 

[Blood Cell Classification Methods and Results](blood_cell_classification.pdf)

### Supervised Machine-Learning Modeling of Changes in Land Surface Temperature based on Agricultural Emissions
Coordinated a team of four graduate students to explore potential correlations between magnitude of agricultural carbon emissions and global land surface temperature. Built and optimized machine learning models using **Keras**, **TensorFlow**, and **SKLearn libraries**. While we succesfully acheived a 51% decrease in prediction error from the baseline model by implementing deep learning and model optimization techniques, our findings reaffirmed the complexity of climate and emission modeling. Additionally, our research highlighted the limitations of and disparities in carbon accounting methods from country to country. 

[Summary of Data and Model Design](ag_emissions.pdf)

### End-to-End Machine Learning API
Developed a FastAPI Application in Python to serve two machine learning models: an SVM for housing price predictions and a pre-trained transformer model from HuggingFace for natural language sentiment analysis. Utilized Docker and Poetry for application and package management. Defined Kubernetes deployment and services from scratch and leveraged minikube for local development and testing. Deployed the application using Azure Kubernetes Services to simulate a real-world production environment. Performed load testing and monitored application performance using Prometheus and Grafana K6.  

![Incoming Request Duration During Load Testing](/imgs/request_dur_project.png)
*Request duration during appliction load testing.*

### Delivery Route Optimization Using Graph DB and Algorithms
Evaluated optimal delivery routes using Bay Area Regional Transport (BART) system for theortical prescription drug distribution company. Built Neo4j graph databse to define relationships between geographic coordinates and transportation times between BART stations. Used a combination of Python, Pandas, and SQL to query and extract results from built-in Neo4j graph algorithms. Employed Louvain Modularity to define logical groupings of BART stations and cross-referenced against regional population density data to identify optimal pick up locations within groupings. Utilized Dijkstra's Shortest Path algorithm to determine shortest paths from the distribution center (source node) to each of the pick up locations. 



