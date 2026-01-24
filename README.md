# Alzheimer-s-Disease-Data-Science-Project
The dataset consists of MRI scan images categorized into four different classes:  
Non-Demented: No signs of Alzheimer’s. 
Very Mild Demented: Early-stage signs of Alzheimer’s. 
Mild Demented: More pronounced symptoms. 
Moderate Demented: Advanced stage.

This project involves the analysis of a dataset containing brain imaging data categorized by the progression of Alzheimer's Disease. The analysis focuses on class distribution, image dimensions, and pixel intensity metrics.

## 📊 Dataset Overview

The dataset is divided into four clinical stages. There is a higher representation of healthy and early-stage samples compared to advanced stages.
**Total Samples**: The dataset consists of over 44,000 images.
Original vs. Augmented: 91.78% (40.38K) of the data are original photos, while 8.22% (3.62K) are augmented.

Class Distribution :
Non-Demented: 12.6K samples.
Very Mild Demented: 11.2K samples.
Mild Demented: 10.0K samples.
Moderate Demented: 10.0K samples.



## 🔍 Key Insights & Image Characteristics

### 1. Dimensional Trends

Analysis shows a distinct correlation between the clinical stage and the average image dimensions. As the severity of dementia increases, the images generally become wider and shorter.StageAvg. HeightAvg. WidthNon-Demented~192.0 ~189.0 Very Mild Demented~191.6 ~191.0 Mild Demented~190.7 ~196.0 Moderate Demented~190.1 ~199.5 2. Visual Intensity Metrics

The following table summarizes the average brightness and intensity levels across the different classes:

| Stage | Avg. Brightness | Avg. Std. Intensity | Avg. Intensity |
| --- | --- | --- | --- |
| **Non-Demented** | 78.99 | 78.97 | 74.59 |
| **Very Mild Demented** | 74.35 | 78.97 | 74.59 |
| **Moderate Demented** | 72.49 | 78.97 | 74.59 |
| **Mild Demented** | 71.32 | 78.97 | 74.59 |

> While brightness decreases as the disease progresses from "Non-Demented" to "Mild Demented," the Standard Intensity and Average Intensity remain constant across all classes at 78.97 and 74.59, respectively.
> 

---

Would you like me to help you write the "Installation" or "Usage" sections for your code to include in this README?
