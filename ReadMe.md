# Segmenting a Human from a Chair UNet model

This project performs image segmentation using PyTorch and Unet. It includes a full pipeline for:

- Loading high-resolution images and JSON-based annotations
- Generating binary masks from annotation data
- Applying image and mask transformations
- Training a segmentation model on the processed dataset

In this specific example, a dataset of people sitting in chairs with corresponding masks of just the person created using LabelMe: https://labelme.io/ is used. 

The data used to train this model is not open source and was personally collected. 

## Getting Started

```
git clone https://github.com/mackenziesnyder/Person-Chair-Segmentation.git
cd Person-Chair-Segmentation
```

Run the .ipynb files. These files were originally run in a Google Colab environment using python3.11, and a T4 GPU


### Author
Mackenzie Snyder
3rd Year Biomedical Engineering @ University of Waterloo
Focus: Machine Learning, Computer Vision, Neurotechnology, Sports Engineering