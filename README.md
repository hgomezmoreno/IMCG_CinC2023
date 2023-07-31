# IMCG_CinC2023
CinC 2023 Paper Materials
___
# Abstract
Due to the lengthy information, irregular structure, and numerous types of distortion and disconnections, analyzing long ECG signals can be difficult. This study suggests a technique that uses neural networks to identify essential traits in cardiac abnormalities, allowing for generalization from a small set of samples. An ECG-to-image conversion is built enabling the use of image processing methods and tools for semantic segmentation for anomaly detection. The ResNet50 network, which is incorporated into the DeepLabv3 architecture, is used to identify ventricular beat fusions and premature ventricular contractions. An established database is used to assess the model's efficacy. The ECG data are converted into images utilizing thresholding and heat maps. PyTorch is used to train the network with optimal hyperparameters, leading to a considerable convergence. The created binary masks mark the found abnormalities with accuracy. The presented method can help medical personnel detect heart anomalies more quickly and accurately by automating the study of long-term ECG readings.
___
![part1_v2_+](https://github.com/hgomezmoreno/IMCG_CinC2023/assets/122869610/e218fbe0-2f9b-44a6-8521-007f5840c88b)
*Conversion from ECG to image.*

![parte2](https://github.com/hgomezmoreno/IMCG_CinC2023/assets/122869610/32a9c112-569c-463b-a8d2-2fa4042bbe6d)
*Segmentation process*
