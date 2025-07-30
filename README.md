# Grad-CAM Visualization with MobileViTv2

A beginner-friendly walkthrough for using Grad-CAM on the MobileViTv2 dataset to generate heatmaps for images classified by the model.

## Motivation

Grad-CAM is a useful tool in computer vision that gives a human-readable visual understanding of what parts of an image a convolutional neural network is using when classifying images. This is especially useful when training on image datasets to make sure that models aren't fitting to features of an image that they aren't supposed to (e.g., text from the camera rather than the animal).

## Setup Instructions

**Pre-requisites:**

- Python 3.10 (recommended)
- Conda (optional but recommended for managing environments)
- Basic familiarity with Jupyter Notebooks

**Steps to set up your environment:**

1. **Clone the repository:**

  ```bash
  git clone https://github.com/PezKid/grad-cam-mobilevit
  cd grad-cam-mobilevit
  ```

2. **Create and activate the conda environment:**

  ```bash
  conda create -n gradcam python=3.10
  conda activate gradcam
  ```

3. **Install required packages:**

  ```bash
  pip install -r requirements.txt
  ```

4. **Start the Jupyter notebook:**

  ```bash
  jupyter notebook GradCAM_MobileViTv2.ipynb
  ```