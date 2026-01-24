## Alzheimer's Disease Data Project

The dataset consists of MRI scan images categorized into four different classes:

Non-Demented: No signs of Alzheimer’s.
Very Mild Demented: Early-stage signs of Alzheimer’s.
Mild Demented: More pronounced symptoms.
Moderate Demented: Advanced stage.

### 1. Class Distribution

To ensure the model learns effectively, I first mapped out our data "population." The dataset is remarkably robust, leaning slightly toward healthy controls to provide a strong baseline for "normal" brain structure.

**Non-Demented:** 12.6K images 
**Very Mild Demented:** 11.2K images 
**Mild Demented:** 10.0K images 
**Moderate Demented:** 10.0K images 

### 2. Visual "Heatmap" & Intensity Analysis

By applying conditional formatting to pixel data, a fascinating trend emerges: **as dementia severity increases, the overall brightness of the images decreases.** This visual "dimming" could be a digital proxy for changes in brain tissue density.

| Stage | Avg. Brightness | Observation |
| --- | --- | --- |
| **Non-Demented** | <br>**78.99** 

 | The brightest images in the set. |
| **Very Mild** | <br>**74.35** 

 | A noticeable drop in luminance. |
| **Moderate** | <br>**72.49** 

 | Continued decline in brightness. |
| **Mild** | <br>**71.32** 

 | The lowest brightness levels detected. |

Note: Interestingly, the Standard Intensity (78.97) and Average Intensity (74.59) remain identical across all categories, suggesting that the "range" of light stays the same, even if the "total" light dims. 

### 3. Authenticity Check (Augmented vs. Original)

To keep the analysis grounded in reality, I tracked the ratio of real-world scans to computer-generated (augmented) images.

**Original Photos:** 91.78% (40.38K) 
**Augmented Photos:** 8.22% (3.62K) 
**The Takeaway:** The project prioritizes high-fidelity, original medical data, using augmentation only as a light "seasoning" to help the model generalize better. 

### 4. Interactive Drill-Down: Shape & Size

Using interactive filtering, I discovered a "Dimensional Drift." There is a physical shift in the images as the disease reaches the "Moderate" stage.

**Healthy Scans:** Tend to be taller (192.0) and narrower (189.0). 
**Moderate Demented Scans:** Shift significantly, becoming shorter (190.1) and wider (199.5). 
