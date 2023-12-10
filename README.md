![Homepage demo banner](DetectionExample.png)

# Information

This repository contains the code and white paper for the demining project using YOLO v8. Data labeling, model training and inference are all handled through Roboflow. 
#### Attention: Please read the white paper for an in-depth overview of the project and its planned stages. 

### Current Stage: Initial Data Collection and YOLO v8 Training

This stage began in October of 2023 and is set to be successfully completed by the beginning of January 2024. Up until now, the initial dataset of landmines has been constructed, with the FPM-1, TM-62 and MON-50 landmines being represented in the dataset at the moment. The algorithm of choice has been trained through Roboflow and is showing encouraging results with the detection of these landmines. On the other hand, the current dataset is currently being cleaned and supplemented by additional images that will need to be labeled and whose quality will need to be verified.

### Next Stage: Sensor Implementation

Equally as crucial as the first stage is the implementation of sensors, which will begin in January of 2024 and end with a drone prototype that has all of the aforementioned sensors. Feedback will be provided at every step of the process by collaborating partners, with the sensors ideally ready for use by the beginning of the summer of 2024. 

## Project Screenshots and Metrics

Data augmentation schemes offered by Roboflow can be effective at simulating different conditions in which landmines may be found while ensuring that the model’s generalization is improved through the increased availability of high-quality data. For example, augmentation techniques involving spatial transformations such as horizontal and vertical flipping, noise and shear have been considered to be effective ways of applying transformations to object detection such that the dataset is diversified. These techniques were already successful in increasing the model’s performance when compared to initial training procedures without augmentations, with the mean average precision (mAP) increasing from 87.5% to 90.8%, precision from 94.6% to 95.6% and recall from 82.2% to 86.7%. 

![Model Metrics](Metrics.png)

![Visualized Model Metrics](GraphMetrics.png)

## Technology Stack

- JavaScript
- [roboflow.js](https://docs.roboflow.com/inference/web-browser)
