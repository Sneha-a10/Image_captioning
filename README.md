# Image_captioningImage Captioning Visualization

->  A Python-Powered Tool for captioning images

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#techonologies-used)
- [Dataset](#Dataset)

##  Overview

The Image Captioning Visualization project is a Jupyter Notebook-based application designed to process and generate captions for images. It enables users to load images and their corresponding captions from a CSV file, preprocess images for analysis, and display them with captions in an organized grid format. This tool is ideal for researchers, data scientists, and machine learning practitioners exploring image captioning datasets or preparing data for model training.

##  Features

* Image Preprocessing: Loads and resizes images to a uniform 224x224 resolution, converts them to RGB, and normalizes pixel values for consistent analysis.
* Caption Display: Wraps captions for readability and pairs them with images in a clean, grid-based visualization.
Dataset Integration: Seamlessly reads image filenames and captions from a CSV file using Pandas.
User-Friendly: Simple, well-documented code with modular functions for easy customization.
Extensible: Easily adaptable for additional preprocessing steps or integration with image captioning models.

##  Technologies Used

Core Libraries:
Python
Pandas (Data manipulation and CSV handling)
TensorFlow (tensorflow.keras) (Image preprocessing)
Matplotlib (Visualization)
Textwrap (Caption formatting)


Environment:
Jupyter Notebook (Interactive development)


Utilities:
Warnings (Suppress unnecessary warnings)


##  Dataset
The project uses a dataset with the following structure:

* **CSV File (captions.txt):** Contains two columns:
    * image: Filenames of images (e.g., 1000268201_693b08cb0e.jpg).
    * caption: Text descriptions for each image.

* **Image Directory:** A folder containing the  8000 images referenced in the CSV file, located at the specified image_path.

**[Flickr8K Image Captioning] (#https://www.kaggle.com/datasets/adityajn105/flickr8k) is the dataset used.** 
