# English-vs-Arabic-image-text-classification

## Overview
This repository hosts a project that utilizes the LeVIT (Lightweight Vision Transformer) model for classifying images based on the language of the text they contain. Specifically, the model is trained to distinguish between images containing Arabic and English text.

## Project Description
The project demonstrates the application of the LeVIT method in the domain of language recognition within images. LeVIT is a transformer-based neural network known for its efficiency in image-related tasks. In this project, it is adeptly employed to classify images as either containing Arabic or English text. After training and testing the model, it is transformed into tflite format to be deployed on edge devices.

## Key Features
- LeVIT Implementation: Detailed implementation of the LeVIT model tailored for the specific task of language classification in images.

- Custom Dataset Handling: A custom dataset class, LangDataset, is implemented for processing and labeling images containing Arabic and English text.

- Model Training and Evaluation: Comprehensive steps for training the LeVIT model on the language dataset and evaluating its performance.

## Installation

To set up this project:

1. Ensure you have Python 3.10 and PyTorch 2.0.1 installed.
2. Install additional dependencies such as Torchvision and PIL.
3. Clone this repository to your local machine.

## Usage
Follow these steps to run the project:

1. Navigate to the cloned repository.
2. Install the required dependencies as listed in the notebook.
3. Execute the Jupyter Notebook to train the LeVIT model and test it on your dataset.
4. Convert the trained model to tflite format


