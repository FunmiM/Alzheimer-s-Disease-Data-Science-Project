# Alzheimer-s-Disease-Data-Science-Project
The dataset consists of MRI scan images categorized into four different classes:  Non-Demented: No signs of Alzheimer’s. Very Mild Demented: Early-stage signs of Alzheimer’s. Mild Demented: More pronounced symptoms. Moderate Demented: Advanced stage.

## Exploratory Data Analysis (EDA) Summary Report

### 1. Class Distribution Analysis

The dataset contains four stages of Alzheimer’s Disease. Upon analysis, I found that the classes are Unbalanced.

Total Images: 44,000
Largest Class: NonDemented with 12800 images
Smallest Class: MildDemented with 10000 images

### 2. Image Quality & Consistency

Visual inspection of samples from each category confirms that the MRI scans are grayscale and properly centered.

Dimensions: All images are approximately [Width x Height] pixels.
Clarity: Brain structures (ventricles and cortex) are clearly visible, allowing for structural feature extraction.

### 3. Intensity & Histogram Analysis

Using pixel intensity histograms, I observed a consistent distribution across all classes.

Background: A high frequency of "0" (black) pixels represents the non-brain area.
Brain Tissue: Most tissue pixels fall between the [Value] and [Value] range.
Finding: There are no significant brightness biases between "Non-Demented" and "Demented" classes.

### 4. Feature Engineering & Augmentation

I calculated the average Texture (Graininess) and Contrast for the dataset.

Mean Brightness: 74.044948
Texture/Contrast: The augmented images appear to maintain the same statistical properties as the original scans.

Conclusion: The dataset is of high quality and is ready to be pre-processed for Machine Learning model training.
