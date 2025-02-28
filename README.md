## Machine Learning for Tumor Detector

This repository contains a machine learning model for classifying medical images using deep learning. The project utilizes VGG19 for image classification.

Table of Contents:

Project Overview

Getting Started

Model Training

License

Project Overview:

This project helps to apply machine learning techniques to medical image classification tasks, such as detecting abnormalities in MRI scans.

Key Features:

Model training on medical imaging datasets.
Evaluation of model accuracy on the test set.

Getting Started:

Prerequisites

    Python 3.10.12
    Required Python packages (see requirements.txt)

Installation

Clone this repository:

    git clone https://github.com/miladtaleb/Tumor-Detector-V2.git
    cd Tumor-Detector-V2

Install the dependencies:

    pip install -r requirements.txt

Download the medical image dataset (e.g., BraTS) and place it in the ./data/ folder.

Train the model:

The dataset should be in the following format:

Input images: MRI slices with jpg extension as one zip file.
Labels: The target labels for classification (tumor/no tumor).

Once the dataset is prepared, you can proceed with training the model.

License:

This project is licensed under the MIT License.
