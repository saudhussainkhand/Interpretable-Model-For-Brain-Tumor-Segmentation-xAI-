# Interpretable-Model-For-Brain-Tumor-Segmentation-xAI
This repository contains code for implementing interpretable model for brain tumor segmentation using Brats-2020 dataset

## Abstract
Brain Tumour Localization and Segmentation from MRI is a challenging task in the field of Medical AI. With the recent advancements many different techniques have been used to help and support the medical personnel’s in detecting the brain tumour with the help of Artificial Intelligence. Though, the Machine Learning Algorithms are proving to be efficient in segmentation of tumours but they do not provide information about their internal decision making. Thus making it difficult to trust and validate. In this project, we have build an interpretable Unet Model for brain tumour segmentation using Gradient-weighted Class Activation Mapping (Grad-CAM) Algorithm and SHapley Additive explanations (SHAP) Library. For this project BraTS2020 benchmark dataset was used. The model used for the segmentation was UNET model. The model achieved quite good scores. The Gradcam was then applied to visualize the important features that model focuses on in an image. Furthermore, the explainability was extended by the use of SHAP library to explain the predictions of multiple models (Random Forest, KNN, SVC, MLP) used to predict the survival days of the patient.

## UNET Model
<img width="398" alt="image" src="https://github.com/saudhussainkhand/Interpretable-Model-For-Brain-Tumor-Segmentation-xAI-/assets/60270854/5ad2483c-4b15-4eda-b7ab-1191f6000a63">

## Segmentation Results
<img width="373" alt="image" src="https://github.com/saudhussainkhand/Interpretable-Model-For-Brain-Tumor-Segmentation-xAI-/assets/60270854/7ccb1c44-5e0f-43f9-9211-52d0e0fe689a">

## GradCam Heatmap
<img width="366" alt="image" src="https://github.com/saudhussainkhand/Interpretable-Model-For-Brain-Tumor-Segmentation-xAI-/assets/60270854/c5f3eee8-e61f-41b3-b680-a3afd4a1ff78">

## SHAP Explanations
<img width="400" alt="image" src="https://github.com/saudhussainkhand/Interpretable-Model-For-Brain-Tumor-Segmentation-xAI-/assets/60270854/e1cb89ba-884b-4350-86ff-f85006d9fff9">

