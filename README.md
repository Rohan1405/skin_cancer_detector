# Skin Cancer Detector using FastAI Library and Pretrained ResNet50 Model
This is a skin cancer detector that has been built using the FastAI library and a pretrained ResNet50 model. It uses a convolutional neural network to classify skin lesion images as either benign or malignant. This project is intended to aid in the early detection of skin cancer and assist medical professionals in making accurate diagnoses.

Installation
 1. Install Python 3.7 or later.
 2. Install the necessary dependencies: pip install fastbook


# Usage
1.Start the Jupyter Notebook 
2.Open the "skincancer.ipynb" notebook in the browser.
3.Run the cells of the notebook to train the model and evaluate its performance.
4.Use the trained model to predict whether a skin lesion is benign or malignant



# Dataset
The dataset used for this project is the HAM10000 dataset, which contains 10,000 dermatoscopic images of pigmented lesions. The images are classified into seven categories: melanocytic nevi, melanoma, benign keratosis, basal cell carcinoma, actinic keratoses, vascular lesions, and dermatofibroma. For this project, we only used the images that were labeled as either benign or malignant.

# Pretrained Model
The pretrained ResNet50 model was used as the backbone of the convolutional neural network. This model has been trained on a large dataset of images and has learned to recognize a wide variety of features. By using this model, we can take advantage of its prelearned features and fine-tune it for our specific task.

# Performance
The model achieved an accuracy of 85% on the test set, which is a good performance given the complexity of the task. However, it is important to note that this model should not be used as a substitute for a medical professional's diagnosis. It is merely a tool that can aid in the detection of skin cancer and assist in making accurate diagnoses.

# Credits
This project was inspired by the FastAI course and uses the FastAI library. The HAM10000 dataset was used for this project, and credit goes to the creators of this dataset. The pretrained ResNet50 model was used as the backbone of the convolutional neural network, and credit goes to the creators of this model.
