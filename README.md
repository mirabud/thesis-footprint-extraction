### Master's thesis "Exploring and analyzing  Deep Learning-based methods for digitized city footprint extraction from aerial images”.
This code is from the master's thesis work on the topic of "Exploring and analyzing  Deep Learning-based methods for digitized city footprint extraction from aerial images”. The thesis explores deep learning-based methods for digitized city footprint extraction from aerial images. The work compares semantic and instance segmentation approaches, including UNET, YOLOv11-Seg, Detectron2, and SAM2, applied to a real-world high-resolution dataset. A pre-processing pipeline was developed to handle large geospatial data, convert shapefiles to model-specific formats, and preserve original coordinates for GIS compatibility. 

### Results
Results have shown that  UNET achieves the highest accuracy for building footprint segmentation, while SAM2 demonstrates superior performance in road extraction. YOLOv11-Seg performs moderately across both tasks, and Detectron2 underperforms compared to the other models. 

The resulting examples are below: 
<img width="1984" height="1192" alt="pred_masks1" src="https://github.com/user-attachments/assets/d54a6019-8637-4597-bdb9-2fd00637cb66" />
<img width="1984" height="1192" alt="pred_masks2" src="https://github.com/user-attachments/assets/91cf07e9-6602-494c-86bd-f579ef07877d" />
<img width="1984" height="1192" alt="pred_masks3" src="https://github.com/user-attachments/assets/41706690-ad2d-43dc-b198-e7c7165387bb" />

About the code: 
There are separate notebooks for SAM2 and Detectron2 training, because I used different kernels for them due to the difficulties of installing the libraries. Additionally, they were postprocessed in their respective notebooks due to the specific characteristics of the models. 


