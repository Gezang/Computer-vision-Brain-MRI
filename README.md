# Computer Vision for classifying brain MRI scans

This repository is for a project in computer vision.

The project compares two models (CNN and SVM) for classifying brain tumor MRIs

## Results
Both models achieved 97.64% classification accuracy on the test set. However, analysis of the confusion matrices revealed differences in how each model distributes its errors across tumor classes — the CNN and SVM make different types of misclassifications despite reaching the same overall accuracy. Full analysis and discussion can be found in report.pdf.

## Structure of the code

The code in [analysis.ipynb](analysis.ipynb) can be used to recreate the results obtained. The code is divided into sections as follows:

1. Data preprocessing
2. Plotting some samples (Augmented)
3. Build and train CNN
4. Build and train SVM
5. Analysis of both models performance.

## Report

The project report can be found in [report.pdf](report.pdf).

## Data:

The dataset was found on Kaggle. To download the dataset visit [Brain-MRI-Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data).
