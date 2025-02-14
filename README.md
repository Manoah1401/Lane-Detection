# Lane Detection on Unstructured Roads
This repository contains code and resources for a lane detection project, focusing on detecting lanes on Indian unstructured roads using deep learning techniques and computer vision.

## Table of Contents
1) Project Overview
2) Key Features
3) Installation
4) Usage
5) Project Structure
6) Results

## Project Overview
This project implements lane detection using deep learning models, focusing on Indian roads where lane markings can be absent or inconsistent. The goal is to create a reliable system that identifies lanes even under challenging conditions such as unstructured roads, worn-out lane markings, or varying weather conditions.

## Key Features
1) Lane Detection: A model that detects lanes on unstructured roads.
2) Transfer Learning: A model trained on structured highways adapted to unstructured roads.
3) Performance Evaluation: Scripts to test model performance and evaluate different metrics.
4) Binary Masking: Generation of binary masks for lanes.
5) Data Handling: Efficient image data loading and processing using NumPy.
6) Model Testing: Scripts to test the model on real-world data.

## Installation
To install and run the project locally, clone the repository and install the necessary dependencies:
1) git clone https://github.com/Manoah1401/Lane-Detection.git
2) cd Lane-Detection
3) pip install -r requirements.txt

Make sure you have the following dependencies installed:
1) TensorFlow
2) NumPy
3) OpenCV
4) Matplotlib
## Usage
1) Data Preparation:

   a) Convert images to NumPy arrays using the `Image_to_numpy.ipynb` script.  
   b) Apply binary masking using the `Single_Image_binary_masking.ipynb` script.

2) Model Training:
   
   a) Use `Lane Detection.ipynb` to train the model on highway data.  
   b) For transfer learning to unstructured roads, use the `Transfer_Learning.ipynb` notebook.

3) Model Testing:

   Test the trained model and evaluate its performance using `Model_Tester_and_Performance_Metrics_Final.ipynb`.
## Project Structure
- Single_Image_binary_masking.ipynb  - Masking scripts
- Image_to_numpy.ipynb               - Converting images to numpy arrays
- Mini project.ipynb                 - Initial model development
- Lane Detection.ipynb               - Lane detection on Indian highways
- Transfer Learning.ipynb            - Transfer learning for unstructured roads
- Model_Tester_and_Performance_Metrics_Final.ipynb - Model testing and metrics
- Data Loader.ipynb                  - Data loading scripts
## Results
1) The model was able to detect lanes with an accuracy of 97% on Indian roads.
2) Transfer learning to unstructured roads improved lane detection in challenging environments.
