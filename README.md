# IMCG_CinC2023
CinC 2023 Paper Materials
___
# Abstract
Due to the lengthy information, irregular structure, and numerous types of distortion and disconnections, analyzing long ECG signals can be difficult. An ECG-to-image conversion is built enabling the use of image processing methods and tools for semantic segmentation that uses neural networks. That segmentation is based on the ResNet50 network, which is incorporated into the DeepLabv3 architecture, and is used to identify ventricular beat fusions and premature ventricular contractions. An established database is used for training and to assess the model's efficacy. The ECG data are converted into images using thresholding and heat maps, and PyTorch is used to train the network. The obtained binary masks mark the found abnormalities with accuracy. The presented method can help to detect heart anomalies more quickly and accurately by automating the study of long-term ECG readings.
___
![part1_v2_+](https://github.com/hgomezmoreno/IMCG_CinC2023/assets/122869610/e218fbe0-2f9b-44a6-8521-007f5840c88b)
<p align="center">
<em>Conversion process from ECG to image</em>
</p>

![parte2](https://github.com/hgomezmoreno/IMCG_CinC2023/assets/122869610/32a9c112-569c-463b-a8d2-2fa4042bbe6d)
<p align="center">
<em>Segmentation process</em>
</p>

