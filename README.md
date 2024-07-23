

# [Creating Simulated Datasetsfor Domain Adaptation to Enhance Vehicle Detection](https://github.com/behnaz-sadeghigol/sadeghigol)


## Overview
<p style="font-size:30px; ">To create our synthetic dataset, we harnessed the capabilities of Unreal Engine Our process involved meticulously constructing a virtual scene that accurately represented the JLTV military machine. This scene included intricate geometry, realistic materials, and precise lighting conditions.By driving the simulated JLTV across five distinct environments (forest, pasture, mountain, snow, and plain) and rendering on it, we generated a diverse set of synthetic data samples. Our Unreal Engine generated synthetic dataset comprises 3043 samples, with 130 reserved for validation and 2913 for training. </p>
 
![image](https://github.com/user-attachments/assets/932a970d-aa59-4e4d-8f7f-5dba3ae9cef0)



## Features

🧠**Render annotations for semantic segmentation, instance segmentation and panoptic segmentation**.

📊 **Evaluate and visualize data**. Compare the synthetic data to the real data against a variety of measures. 

🔄 **Preprocess, anonymize and define constraints**. Control data processing to improve the quality of synthetic data, choose from different resolution of images.

## Introduction

<p style="font-size:40px; "> Oshkosh Defense has supplied over 22,000 Joint Light Tactical Vehicles [JLTV](https://oshkoshdefense.com/vehicles/light-tactical-vehicles/jltv) to the United States military and allied foreign governments. The JLTV, designed for improved performance, payload, and protection, is a specialized vehicle not widely available in many countries. Obtaining a comprehensive real-world dataset for JLTV object detection is challenging. However, the existence of the JLTV model in the Unreal Engine marketplace provides an opportunity to leverage synthetic data generation. Creating a synthetic JLTV dataset in Unreal Engine allows access to a diverse set of labeled data for training and validating object recognition models. This approach is particularly valuable for rare or specialized objects, overcoming real-world data limitations. After generating the synthetic dataset, a real labeled dataset collected from the Internet and manually annotated using the **CVAT** tool. This combination of synthetic and real-world data can be useful for domain matching, which is the process of adapting a model trained in one domain (such as synthetic data) to perform well in a different domain (such as real-world data)[6]. By using synthetic and real-world data, you can improve the performance and robustness of your object recognition model. The creation of a **synthetic JLTV dataset**, combined with real-world data, demonstrates a practical approach to addressing data availability challenges in specialized domains. Researchers and practitioners working on object detection tasks, especially in scenarios with scarce real-world data, can benefit from this methodology. </p>

[JLTV Dataset](https://github.com/behnaz-sadeghigol/sadeghigol/blob/main) is an open-source, developer-first way to anonymize PII, generate synthetic data and sync environments for better testing, debugging and developer experience.

## Unreal Engine

<p style="font-size:40px; "> 
 **Unreal Engine**, a powerful game engine and simulation platform, proves effective for generating synthetic data using a **‘Simulation-Based Approach.’** Its superior ability to create realistic scenes surpasses that of other simulators, making it ideal for producing high-fidelity artificial images. Unreal Engine provides a robust toolkit for developing 3D models, textures, and environments, forming the basis for various synthetic data types, including images, point clouds, and sensor datasets. In our methodology, we harnessed Unreal Engine’s marketplace assets and intricate scenes to construct comprehensive synthetic datasets. Our rendered scenes featured natural landscapes, enhancing the realism of our simulations. Leveraging existing plugins, we achieved automatic and accurate label generation for the synthetic data, streamlining the dataset preparation process. </p>

## [Synthetic Dataset Generation](https://github.com/behnaz-sadeghigol/sadeghigol/blob/main/datasets.md)

<p style="font-size:40px; "> To create our synthetic dataset, we harnessed the capabilities of Unreal Engine Our process involved meticulously constructing a virtual scene that accurately represented the JLTV military machine. This scene included intricate geometry, realistic materials, and precise lighting conditions.By driving the simulated JLTV across five distinct environments (forest, pasture, mountain, snow, and plain) and rendering on it, we generated a diverse set of synthetic data samples. Our Unreal Engine generated synthetic dataset comprises 3043 samples, with 130 reserved for validation and 2913 for training. </p>

![image](https://github.com/user-attachments/assets/88520148-ae08-4a2f-bb6d-4b435fa72804)

![image](https://github.com/user-attachments/assets/b2b20e86-3dd7-4022-b904-3f2ff5fdc6a5)


## [Real Dataset Collection](https://github.com/behnaz-sadeghigol/sadeghigol/blob/main/datasets.md)

<p style="font-size:40px; "> To complement our synthetic dataset, we collected a real-world dataset of the JLTV military machine. We crawled the internet to gather 65,634 images of the JLTV from various sources, including online forums, news articles, and manufacturer websites. For annotation, we utilized the CVAT (Computer Vision Annotation Tool) [4], which allowed us to manually label the JLTV objects within the images. This process resulted in a total of 30,212 test samples, 33,682 training samples, and 1,740 validation samples. </p>

## Compared to existing datasets with vehicle annotation

<p style="font-size:40px; "> Table 1 compares JLTV dataset to other vehicle datasets. Our dataset stands out due to its combination of real-world and synthetic data. We leveraged the powerful Unreal Engine to create highly realistic scenes, simulating real-world conditions. The dataset includes 68,677 annotated samples captured from diverse camera viewpoints. Our JLTV dataset’s high fidelity, diverse viewpoints, and automatic generation annotations make it a valuable resource for advancing object detection technologies. </p>

![image](https://github.com/user-attachments/assets/0034e5d4-b828-471f-b6fa-b618ec3d8f26)

