## Alzheimer's Disease Data Project

### 1. Class Distribution Dashboard

The dataset exhibits a balanced distribution with a slight majority in the healthy control group. This distribution is critical for understanding model bias during training. 

* 
**NonDemented:** 12.6K images 


* 
**VeryMildDemented:** 11.2K images 


* 
**MildDemented:** 10.0K images 


* 
**ModerateDemented:** 10.0K images 



### 2. Heatmap Analysis (Pixel Intensity Trends)

The following intensity metrics show how visual data varies across dementia stages. Notably, brightness decreases as the severity of the condition progresses from Non-Demented to Mild Demented. 

| Stage | Avg. Brightness | Avg. Std. Intensity | Avg. Intensity |
| --- | --- | --- | --- |
| **NonDemented** | <br>**78.99** 

 | 78.97 

 | 74.59 

 |
| **VeryMild Demented** | 74.35 

 | 78.97 

 | 74.59 

 |
| **ModerateDemented** | 72.49 

 | 78.97 

 | 74.59 

 |
| **MildDemented** | <br>**71.32** 

 | 78.97 

 | 74.59 

 |


### 3. Comparative Analysis (Augmentation vs. Original)

A comparison was conducted to measure the data balance between raw captured images and those generated through augmentation techniques. 

* 
**Original Photos:** 40.38K images, accounting for **91.78%** of the dataset. 


* 
**Augmented Photos:** 3.62K images, accounting for **8.22%** of the dataset. 


* 
**Insight:** The dataset relies heavily on original data, using augmentation as a minor supplement to enhance model generalization. 



### 4. Interactive Filtering (Dimensional Analysis)

Users can filter the dataset by "Stage" to observe significant changes in image metadata. A drill-down into image dimensions reveals a physical trend. 

* 
**Dimensional Drift:** There is a clear inverse relationship between dementia severity and image dimensions. 


* 
**ModerateDemented Images:** Tend to be shorter (Avg. Height ~190.1) but significantly wider (Avg. Width ~199.5). 


* 
**NonDemented Images:** Tend to be taller (Avg. Height ~192.0) but narrower (Avg. Width ~189.0). 
