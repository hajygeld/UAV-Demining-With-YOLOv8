![Homepage demo banner](https://media.roboflow.com/inference-demo/rf-homepage-demo-banner.png?updatedAt=1680886879894)

  <div align="center">
      <a href="https://youtube.com/roboflow">
          <img
            src="https://media.roboflow.com/notebooks/template/icons/purple/youtube.png?ik-sdk-version=javascript-1.4.3&updatedAt=1672949634652"
            width="3%"
          />
      </a>
      <img src="https://github.com/SkalskiP/SkalskiP/blob/master/icons/transparent.png" width="3%"/>
      <a href="https://roboflow.com">
          <img
            src="https://media.roboflow.com/notebooks/template/icons/purple/roboflow-app.png?ik-sdk-version=javascript-1.4.3&updatedAt=1672949746649"
            width="3%"
          />
      </a>
      <img src="https://github.com/SkalskiP/SkalskiP/blob/master/icons/transparent.png" width="3%"/>
      <a href="https://www.linkedin.com/company/roboflow-ai/">
          <img
            src="https://media.roboflow.com/notebooks/template/icons/purple/linkedin.png?ik-sdk-version=javascript-1.4.3&updatedAt=1672949633691"
            width="3%"
          />
      </a>
      <img src="https://github.com/SkalskiP/SkalskiP/blob/master/icons/transparent.png" width="3%"/>
      <a href="https://docs.roboflow.com">
          <img
            src="https://media.roboflow.com/notebooks/template/icons/purple/knowledge.png?ik-sdk-version=javascript-1.4.3&updatedAt=1672949634511"
            width="3%"
          />
      </a>
      <img src="https://github.com/SkalskiP/SkalskiP/blob/master/icons/transparent.png" width="3%"/>
      <a href="https://disuss.roboflow.com">
          <img
            src="https://media.roboflow.com/notebooks/template/icons/purple/forum.png?ik-sdk-version=javascript-1.4.3&updatedAt=1672949633584"
            width="3%"
          />
      <img src="https://github.com/SkalskiP/SkalskiP/blob/master/icons/transparent.png" width="3%"/>
      <a href="https://blog.roboflow.com">
          <img
            src="https://media.roboflow.com/notebooks/template/icons/purple/blog.png?ik-sdk-version=javascript-1.4.3&updatedAt=1672949633605"
            width="3%"
          />
      </a>
      </a>
  </div>

# Information

This repository contains the code and white paper for the demining project using YOLO v8. Data labeling, model training and inference are all handled through Roboflow. 
#### Attention: Please read the white paper for an in-depth overview of the project and its planned stages. 

### Current Stage: Initial Data Collection and YOLO v8 Training

This stage began in October of 2023 and is set to be successfully completed by the beginning of January 2024. Up until now, the initial dataset of landmines has been constructed, with the FPM-1, TM-62 and MON-50 landmines being represented in the dataset at the moment. The algorithm of choice has been trained through Roboflow and is showing encouraging results with the detection of these landmines. On the other hand, the current dataset is currently being cleaned and supplemented by additional images that will need to be labeled and whose quality will need to be verified.

### Next Stage: Sensor Implementation

Equally as crucial as the first stage is the implementation of sensors, which will begin in January of 2024 and end with a drone prototype that has all of the aforementioned sensors. Feedback will be provided at every step of the process by collaborating partners, with the sensors ideally ready for use by the beginning of the summer of 2024. 

## Project Screenshots and Metrics

![Model Metrics](Metrics.png)

![Visualized Model Metrics](GraphMetrics.png)

## Technology Stack

- JavaScript
- [roboflow.js](https://docs.roboflow.com/inference/web-browser)
