# Potato-Disease-Detection
This repository contains code and resources for detecting diseases in potato plants using deep learning techniques. The project leverages convolutional neural networks (CNNs) to classify images of potato leaves into different disease categories.

## Table of Contents
* Introduction
* Features
* Installation
* Usage
* Dataset
* Model Training
* Results
* Contributing
* License
* Contact

## Introduction
Potato diseases can significantly reduce crop yield and quality, affecting the livelihood of farmers and the food supply chain. Early detection and classification of these diseases are crucial for timely intervention. This project aims to automate the process of disease detection using image classification techniques.

## Features
* Classification of potato leaf images into multiple disease categories.
* Pre-trained models and fine-tuning capabilities.
* Simple and user-friendly interface for image upload and prediction.
* Visualization of model performance metrics.

## Installation
To run this project locally, follow these steps:
* Clone the repository:
```
git clone https://github.com/innocentodaga/potato-disease-detection.git
cd potato-disease-detection
```
* Create a virtual environment:
```
python -m venv venv
source venv/bin/activate # On Windows use `venv\Scripts\activate`
```
* Install the dependencies:
```
pip install -r requirements.txt
```
* Download the dataset:
You can download the dataset from:
```https://www.kaggle.com/search?q=potato+leaf+disease```

## Usage 
To start the application, run the following command:
```
python main.py
```
This will start a web server that you can access in your browser at http://localhost:5000. You can upload images of potato leaves to get predictions on the disease type.

## Dataset
The dataset used in this project contains images of potato leaves categorized into different disease types. The dataset is organized into the following structure:
```
training/
    ├── PlantVillage/
    │   ├── healthy/
    │   ├── early_blight/
    │   └── late_blight/
    └── training.txt
```

## Model Training
To train the model from scratch or fine-tune a pre-trained model, run the following file:
```
training.ipynb
```

## Results
After training the model, you can evaluate its performance using the test dataset. The evaluation metrics and confusion matrix will be displayed, showcasing the model's accuracy and classification performance.

## Contributing
We welcome contributions to improve this project! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.
I want to also take this appreciate codeBasics channel for the great work. This is my first ML project so all the most of the effort was from codeBasics

## License
This project is licensed under the MIT License.

## Contact
If you have any questions or need further assistance, please feel free to contact me at innocentodaga111@gmail.com.

