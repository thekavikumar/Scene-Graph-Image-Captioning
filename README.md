# Scene Graph Image Captioning

## Introduction

Welcome to the Scene Graph Image Captioning repository! This project provides a convenient way to generate image captions using scene graph generation. The internal code includes significant alterations, such as new dataloaders and the implementation of the function 'im2scenegraph'. This function allows users to pass any custom image and receive a complete scene graph along with visualizations and captions within the same notebook. This repository aims to offer a straightforward method for running the SGG repository without the hassle of extensive setup.

Base paper: Tang et al. "Unbiased Scene Graph Generation from Biased Training", CVPR 2020. (https://arxiv.org/abs/2002.11949)

## Instructions to run the code

To run the scene graph generator, you can simply download the Python Notebook file titled 'K_SGG.ipynb' (https://github.com/thekavikumar/Scene-Graph-Image-Captioning/blob/main/K_SGG.ipynb), upload it to Google Colab or Amazon SageMaker, and run it to completion. No need to clone this repository and do any installation separately; the notebook takes care of everything.

This repository has been built and tested on Python 3 (PyTorch 1.6 Python 3.6 GPU Optimized) kernel on a ml.g4dn.xlarge instance on Amazon Sagemaker, and also on Google Colab.

## Tech Stack Used

- **Python**: For scripting and running the scene graph generator.
- **PyTorch**: For deep learning and scene graph generation.
- **Jupyter Notebook**: For an interactive coding and visualization environment.
- **FastAPI**: For creating the backend API.
- **ReactJS**: For developing the frontend user interface.
- **Amazon SageMaker**: For cloud-based model training and deployment.
- **Google Colab**: For running and testing the notebooks.

## About

Developed by Kavi Kumar. For more projects, visit [my GitHub](https://github.com/thekavikumar).
