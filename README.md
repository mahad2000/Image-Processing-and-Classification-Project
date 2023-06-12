# Image-Processing-and-Classification-Project
This project focuses on image processing and classification using MATLAB. The goal of the project is to enhance the quality of images and automate their classification using machine learning techniques. The following sections provide an overview of the project and instructions on how to run and use the code.

Project Description
The project consists of a MATLAB script that performs various image processing tasks, including image pre-processing, feature extraction, and classification. The main functionalities of the code are as follows:

Image Pre-processing: The code applies a series of image pre-processing techniques to improve image quality. These techniques include converting images to grayscale, removing noise using median filtering, enhancing contrast, histogram equalization, and contrast stretching.

Feature Extraction: The code calculates color histograms for the original images and extracts Local Binary Pattern (LBP) features from the pre-processed images. These features serve as the input for the subsequent classification step.

Classification: The code trains three classifiers, namely Support Vector Machine (SVM), Decision Tree (DT), and Random Forest (RF), using the extracted features. It then predicts the labels of test images using the trained classifiers.

Performance Evaluation: The code evaluates the performance of the classifiers by calculating metrics such as accuracy, precision, recall, and F1 score. These metrics provide insights into the effectiveness of the classification algorithms.

Getting Started
To run the code and use the project, follow these steps:

Ensure you have MATLAB installed on your machine.

Download or clone the project repository from [GitHub link].

Open MATLAB and navigate to the project directory.

Modify the dataset_folder variable in the code to set the path to your dataset folder containing the images.

Run the MATLAB script to execute the image processing, feature extraction, and classification steps.

After execution, the code will display the performance metrics of the classifiers, providing an evaluation of their accuracy, precision, recall, and F1 score.

Project Structure
The project directory contains the following files:

main_script.m: The main MATLAB script that performs the image processing, feature extraction, classification, and evaluation steps.

calculate_metrics.m: A helper function that calculates performance metrics (accuracy, precision, recall, and F1 score) based on true and predicted labels.

Dataset
Ensure that your dataset follows the specified structure:

The dataset folder should contain subfolders, each representing a specific class or category of images.

Within each subfolder, place the corresponding images in any common image format (e.g., JPEG, PNG).

Exclude the 'filtered_images' folder from the dataset, as it will be automatically created and used by the code for saving pre-processed images and extracted features.

Dependencies
The project code relies on MATLAB's built-in functions and libraries for image processing and machine learning. No additional external libraries are required.

Results and Output
The code generates the following output and results:

Display of performance metrics (accuracy, precision, recall, and F1 score) for each classifier.

Creation of the 'filtered_images' folder within each subfolder of the dataset, containing the pre-processed images.

Saving of the extracted LBP features as .mat files within the 'filtered_images' folder.

Prediction of labels for the test images using the trained classifiers.
