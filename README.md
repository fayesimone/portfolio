# Projects

## AgriMed: Semantic Segmentation for Cropland Diagnostics

Led strategic vision and technical implementation of semantic segmentation model for detection of corn and soybean cropland defects from multi-spectral aerial imagery. Utilized both structured and unstructured data. Built training pipeline using **Python**, **Pytorch**, and **Transformers** training API for fine-tuning SegFormer model. Utilized **AWS SageMaker** for data management, model training, validation, and endpoint hosting. Engaged with industry stakeholders to tailor frontend user interface to meet small-scale farmers’ needs.

<br />

## CliMistral: Fine-Tuned Mistral Model for Climate Q&A

Domain fine-tuned the pre-trained Mistral Instruct large language model for climate QA generation using **Pytorch**. Leveraged QLoRA parameter-efficient fine-tuning methodology to reduce compute resources needed for training and reduce model energy consumption. Clearly communicated complex machine learning techniques and results both verbally and in written report to a technical audience of peers and professors.

[CliMistral Furthering Efficiency and Capabilities of Large Language Models in the Climate Domain](climistral.pdf)

<br />
## Blood Cell Classification
![Histogram of Oriented Gradient Feature Extraction By Class](/imgs/hog_example.png)
*Visualizing feature extraction for histogram of oriented gradients by blood cell class.*


Ideated and implemented an image processing pipeline in **Python** to extract novel feature vectors and perform dimensionality reduction for images of healthy blood cells. Built, optimized, and compared performance of a combination of simple and deep learning classification models using **TensorFlow** functional API. The simplest and lowest cost logistic regression model achieved an 82% test accuracy, while the highest performing neural network achieved a 94% test accuracy. The high performance of both the simple and complex models indicate that the extracted features are highly descriptive and sufficiently unique between classes. Additionaly, while extraction of complex features using convolutional nerual networks aids in improving accuracy of blood cell image classification, simpler features, like luminance histograms and histogram of oriented gradients, are highly descriptive and far less computationally expensive to extract. 

[Blood Cell Classification Methods and Results](blood_cell_classification.pdf)

<br />
## End-to-End Machine Learning API
Developed a **FastAPI** Application in **Python** to serve two machine learning models: an SVM for housing price predictions and a pre-trained transformer model from HuggingFace for natural language sentiment analysis. Utilized **Docker** and Poetry for application and package management. Defined **Kubernetes** deployment and services from scratch and leveraged minikube for local development and testing. Deployed the application using **Azure Kubernetes Services** to simulate a real-world production environment. Performed load testing and monitored application performance using Prometheus and Grafana K6.  

![Incoming Request Duration During Load Testing](/imgs/request_dur_project.png)
*Request duration during appliction load testing.*

<br />
## Supervised Machine-Learning Modeling of Changes in Land Surface Temperature based on Agricultural Emissions
Coordinated a team of four graduate students to explore potential correlations between magnitude of agricultural carbon emissions and global land surface temperature. Built and optimized machine learning models using **Keras**, **TensorFlow**, and **SKLearn libraries**. While we succesfully acheived a 51% decrease in prediction error from the baseline model by implementing deep learning and model optimization techniques, our findings reaffirmed the complexity of climate and emission modeling. Additionally, our research highlighted the limitations of and disparities in carbon accounting methods from country to country. 

[Summary of Data and Model Design](ag_emissions.pdf)
