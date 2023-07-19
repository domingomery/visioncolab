![Logo](https://github.com/domingomery/visioncolab/blob/main/visioncolab.png)


# visioncolab
Google colab's for image processing, pattern recognition and computer vision
by [Domingo Mery](https://domingomery.ing.puc.cl/)



# Table of Contents

## [Image Processing](https://github.com/domingomery/visioncolab#image-processing)
* [Basic Image Processing](https://github.com/domingomery/visioncolab#-basic-image-processing)
* [Spatial Domain](https://github.com/domingomery/visioncolab#-image-processing-in-spatial-domain)
* [Frequency Dommain](https://github.com/domingomery/visioncolab#-image-processing-in-frequency-domain)
* [Image Restauration](https://github.com/domingomery/visioncolab#-image-restauration)
* [Morphology](https://github.com/domingomery/visioncolab#-morphology)
* [Segmentation](https://github.com/domingomery/visioncolab#-segmentation)
* [Color Processing](https://github.com/domingomery/visioncolab#-color-processing)

## [Pattern Recognition](https://github.com/domingomery/visioncolab#pattern-recognition-1)
* [Feature Extraction](https://github.com/domingomery/visioncolab#-feature-extraction)
* [Feature Selection and Transformation](https://github.com/domingomery/visioncolab#-feature-selection-and-transformation)
* [Classification](https://github.com/domingomery/visioncolab#-classification)
* [Performance Evaluation](https://github.com/domingomery/visioncolab#-performance-evaluation)

## [Geometry in Computer Vision](https://github.com/domingomery/visioncolab#geometry-in-commputer-vision)
* [Basics](https://github.com/domingomery/visioncolab#-basics)
* [Geometric Transformations](https://github.com/domingomery/visioncolab#-geometric-transformations)
* [One View](https://github.com/domingomery/visioncolab#-one-view)
* [Two Views](https://github.com/domingomery/visioncolab#-two-views)
* [Multiple Views](https://github.com/domingomery/visioncolab#-multiple-views)


## [Deep Learning in Computer Vision](https://github.com/domingomery/visioncolab#deep-learning-in-computer-vision)
* [Image Classification](https://github.com/domingomery/visioncolab#-image-classification)
* [Transfer Learning](https://github.com/domingomery/visioncolab#-transfer-learning)
* [Facial Analysis](https://github.com/domingomery/visioncolab#-facial-analysis)
* [Human Analysis](https://github.com/domingomery/visioncolab#-human-analysis)
* [Object Detection](https://github.com/domingomery/visioncolab#-object-detection)
* [Tracking](https://github.com/domingomery/visioncolab#-tracking)
* [Segmentation](https://github.com/domingomery/visioncolab#-segmentation-using-deep-learning)
* [GAN](https://github.com/domingomery/visioncolab#-generative-adversarial-network-gan)
* [Anomaly Detection](https://github.com/domingomery/visioncolab#-anomaly-detection)


___

# Image Processing

## + Basic Image Processing

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1M8-zYkEmF6vrhrFPTCsENFfxZsetaIL0) Introductory Example: Rice segmentation (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/100zqZBV51j2hP6yjKOrkjxvpsSiLLuh2)
Sampling (spatial and grayscale sampling) (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1gfSdlVgzd3abygf8XB0I2F62rpzlh8SK)
Basic color segmentation (+)

## + Image Processing in Spatial Domain

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Z5ok0Cr7ynp_jCZ-DM8S-6u8DtOZfBOI)
Geometric Transformation (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1yYoH_UcDlqCXD-EMAI6moU9m7G7dScJ0)
Equalization of Histogram (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1bkjxaD_d26MbwHeoHA2AxgkT37NNYnsQ)
Filtering with Masks (kernels) (+)

## + Image Processing in Frequency Domain

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1I_WXzkk-9eK9_ZMLvByU9uUTgSmqIjJf)
1D Convolution (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17Vs-z4KIsgzOc_h3KWFZko2gPOvPRRfY)
1D Fourier Transform for Audio Signals (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1E4CtsHpohsNRBXwJotORrmTGvGpAQDGM)
2D Filtering uisng Fourier (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1kmwRgPoca3sEboUTdHTuIFqpKbPOu2I5)
Homomorphic Filter (+)

## + Image Restauration
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lcq5BYnD8ITJEAPXLY5q9m6TM4MIt9oS)
Basic Image Restauration (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1VjtFI8hzY7Boh6hmrMDtiRZ5PcOh0Rh0)
Wiener Filter (+)

## + Morphology
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17of6vMplOQ5i1VVoUzkMCw8VEHx7EVp-)
Erosion, Dilatio, Opening, Closing, Skeletization, Filling-Holes, Gradient (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17IeANV0SyAt3C1PGPPjpgcIbgSqesgCc)
Top Hat Filter (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1IXVXu-tbLuUtYEngT6YQ1OLzu8bmxC72?usp=sharing)
Median Filter (+)

## + Segmentation
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1cNxGiXc132_o1YiAdVP5fWBdlTbuTKK2)
Region Growing (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1tWpCZji-YhMFXQLg0OJ9L_UFb7jwD6Vg)
Region Detection using OTSU, MSER, etc. (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1rIbxOKFnoiOVOEKDVNCzM4JpL2M0hVUc)
Edge Detection (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/13DOIjxeyXxuPX_G41_ltur8jBMMTsUJ0)
Hough Transform (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zEA0APG3hRL7VKzcjaWYysC5fdRa9_l_)
Watershed (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ohr3yh0bFkueONUEGaHa5F67zlSf3aTy)
Motion Segmentation (+)

## + Color Processing
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fOO0N4TUTVuWZlhHvgJZDloVMXe445KE)
Color Segmentation using K-means (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1CiPBYICHR4z0F84IQDBS956mJkbe5EJV)
Color Segmentation using Hich Contrast Images (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1cSjA9nThCXbuO2zb97zJpcMP8sqNAqE8)
Color Image Enhancement (+)

(+) Tested in July, 2023
___


# Pattern Recognition


## + Feature Extraction


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1y1S5cWo81uWrSqO3kAkaCHb80cJZqb_R) 
Fourier Descriptors (+)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1as-P-0jA2QePQ9bhnds9_YQZP2n-GvPQ) 
Geometric features (basic, elliptical and moments) (+)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/10kkY5bQD6m1E_Iz5ECPnFrx2xia3A1YE) 
Intensity Features (basic, contrast and Crossing Line Profile) (+)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1-YIkUsTifUEZRmTOiUjJHTZ7j0forPkT) 
Face Recognition using Local Binary Patterns (LBP) (+)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1gdYVNc92Col5pitNJ46C-iio3lZ5nU4U) 
Texture Recognition using LBP, Haralick and Gabor features (+)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1PCVaiHvR6-RmF1C7AS42uon_FIAXICEh) 
Pedestrian Detection using Histogram of Gradients (HoG) (+)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1mPt9MI2ytByR23KpmCveQnP4AbeTvb7k) 
Cow Biometrics using SIFT (+)



## + Feature Selection and Transformation

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1kXMoYW760sig5xZRBBIA0L9vnxcRU8Nw) 
5-Chracter Recognition using Sequential Forward Selection (SFS) (+)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1v1v6qxWkOTmd20cqNOgc5v8jpNWlhgXQ) 
Basic Feature Selection and Transformation: SFS, Exhaustive Search, PCA, PLSR, ICA, etc. (+)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1m5FjawGtIJybkURabnbimBIk7ycfN2bw) Face Recognition with LBP using PCA, ICA and PLSR (+)


## + Classification

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1BnBLAYW-3DLT1KAbD-0x2Mx3hN4nJbA4) 
Collection of Methods for Visualization of Feature Space (+)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1aUqwwueR5dG2_yZ5gGN_NOSppqsvkoaW) 
Basic Classifiers (KNN, Bayes, LDA, QDA, Mahalanobis) (+)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1xIaz5MQgA3F1-vsr5aF0vXo2uqxigm0I) 
Setting Hyperparameter K of KNN using Validation Dataset (+)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1mt1zthdKhgjqcb5D5Rk-j6QIzOxt5itr) 
Neural Networks (from scratch and using sklearn) (+)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1y26nAEUEiiahHx92_jAMrBWipwFZ5BSP) 
Support Vector Machines (SVM) (+)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1Ov_XODfq3fgPI1kW9jSs0U96DNbO3qhu) 
Exhaustive Search of the Best Classifier (+)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/15G9Xm0Pz4g3fXlgqnVqCEpzdqv6ghItN)
Neural Networks for MNIST dataset (+)

## + Performance Evaluation
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1HwNGUGiVzwVC4e5BvSImmTs0m2uhvoyL)
Accuracy Estimation (Hold-Out, Cross-Val, Leave-one-out) and Model Selector **(NEW)**

(+) Tested in July, 2023

___

# Geometry in Commputer Vision

## + Basics
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/146tZRDi1aMUcAEUHICZm9u5n5tkYe8P2) Points and lines in homogeneous coordinates (*)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1LJcOcxEEY5Kvf6hGyl3nyZRbPtZ3jIfD) Pose orientation of a face using Landmarks (*)

## + Geometric Transformations
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10D7Q7r11MuWL2-fNRt2lSqCpSVkvytin) 2D Transformations and Homography (*)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ntbUB7Dc3is7fxu3Z6at46DdOeK-nJO3) 3D Transformations (*)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YF6EUdH8PhAaPfmGfvBZ6HMKTQUcvBlg) 3D Reconstruction (*)


## + One View
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1aCH-K2fCE28dp7-rNrwLEfOs0EZ-rlCD?usp=sharing) Perspective Correction using Homography (*)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1IMUT3diQ3be7DOV2Vp4xbT831rFtfEH5) Camera Calibration (*)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1c1RFOMTk5sNxoTyFieeBEG4BLxZSv_NI) Camera Calibration (*)

## + Two Views
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1JMA_rgIINWX1xaFYZJOaI6qgY-Mu6aha?usp=sharing) Epipolar Geometry (two views) (*)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1vmC5xiECedB0XGDWXZnoM5H9ghmaJB2P?usp=sharing) Estimation of Fundamental Matrix using Corresponding Points in Two Views (*)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OYVC7PnRYyrqcPPIVrU7Rp0Sd8bpqHCb?usp=sharing) Estimation of a Line using RANSAC (*)


## + Multiple Views

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1cxaDUQqbwYWdbfEyIqP_he3RbDh4vb8l?usp=sharing) Mosaics using SIFT (*)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1T8FIaD3EJwBBM9dwdAaPTDIsRVKeK6De) Trifocal Geometry (three views) (*)

(*) Updated in July-2023, some of them in Spanish

___

# Deep learning in Computer Vision

## + Image Classification

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1zXkffKtspfIrLIdxLeEGx0uxeSnyd0B-) Clasification of Eyes and Noses (two classes) (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1g5hjIdQW0q-xH6g0a2uCaRTET0ngEIyi) Defect detection in aluminum wheels (two classes) (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1wvbWbDkdIyJ_JW9OcloE-s4dH5OH6knd) Skin Lesion Recognition (two classes) (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1SfwPxAV46KrFOIs0546fSSIKgEwPXYCO) Clasification of Dogs and Cats (two classes) (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1w1TzZQaN7d3CyfAV7fUklRXdSPTv3Dfh) Covid recognition in Lung X-ray images (three classes) (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Suqs0ml5YoZ0e6HxbF29i044yzUc_AOP) Clasification of Pedestrians with Bikes (three classes) (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1E5IvgFQK_IJd08CjEgp-fISF6jOklDYS) Clasification of Skin Lesion Recognition (seven classes) (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1voq418i9PtdZitUOXd4TPIsEX6AzBAWz) ARLNET (Atterntion Resisual Learning blocks) (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OnaLDIaYgBpKAC0FTK_5a8vyvQwgzFD8?usp=sharing) EfficientNet (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/11fC911p8-oSAipmisoP-XbGIo7BgP_0_) Visual Transformes (from library HuggingFaces) (+)

(+) Tested in July, 2023


## + Transfer Learning

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](train_loader) Clasification of Lungs (normal, Covid-19 and pneumonia using pre-trained ResNet18) (+)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ZY6RaR_fXrqjQbNpqhOEm8GVBEYdowki) Transfer Learning with several Pretrained Models from PyTorch (+)

(+) Tested in July, 2023



## + Facial Analysis
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1gM8JHeEkGudpAmGjiJARB-3-Sgo_EwW2) Face Detection 

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1VgmFdJ2dr0DEWuoP6AiXeW2pxNRZYPEk) Face Recognition (1:1) with ArcFace (face verification) 

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1VOkU_E7y4lslkRcL9OP4R2CkOoOVIq9Z) Face Recognition (1:1) with AdaFace (face verification) 

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Wz0TUOu97eWAijhBV57KjERuzN-SqAGG) Face Recognition (1:N) with ArcFace (face recognition) 

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-kgtjGqLWM8773T9dF9nTqua27twNOLP) Age and Gender Recognition

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/13BW4jUgkqZ8whbiUcM-wDdf1eULQAgCP) Face Expression Recognition

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1eWYjdlSWjk42SZs-AFrUGAMKjQWyryd9) Landmark Detection (68 face landmarks) 

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1vfc71PbQvomZ0d95oTBHNqs5HfNArS7L) Face Geometric Mesh

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1jGFQK_e2fU3aW_MSwnqNpiRVeV0ku-Ac) Estimation of Head Pose

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Fe7gj1KmpHz5GjnVA5Eo02TaXZ7uts3O) Mask Detection in Face using YOLOv5

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nwZpQHKStD6EffAcWFBL5m3gV9Zi6yWp) Eye and Mouth Detection using YOLOv5

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1WrG0uO31Z9pmsuhrP0UEMX9fRe_gSGWt) Restauration of Image Faces using GAN 

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1vFaJHyed5kKWaORaz5Fk6meh_duoCm-x) Face Verification Explanation (Minus, Plus, AVG, SEQ, LIME, RISE)


## + Human Analysis
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1qjgjQ9HLoIrgsAQHmazAXf4YsvB1Bx6D) Detection of Human Pose using OpenPose 


## + Object detection
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1XgViuzkAge2QbUwfjcbUAnANb4xPXbdL) Detection of Eye and Mouth using YOLOv5

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YClT3SsWXL2BypXgEP8T4T-zqeWjnTI_) Defect Detection in Aluminum Castings using YOLOv5

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OPi-4ogz7ySpgLLoGQyCrpNPB7wUcOYZ) Detection of Threat Objects in Baggage using YOLOv5

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DoGA4RHoEE3OtlyoA-pJx-TiHY1gd5mP) General Object Detection using YOLOv5 (with no training)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1jihgbPicjh9VPuQfkdBminSNT3JJWdG3) OCR - Optical Chracter Recognition (OCR) using pytesseract

## + Tracking
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1AfB_f8abUoRJmMx-FpVMdTBnXtV9FXGn) Tracking of Multiple Objects in Videos using YOLOv5


## + Segmentation (using Deep Learning)
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1_aXBWHWTSbkpQgwrYJsubrkRlqeKQGWa) Segmentation of Skin Lesions using UNet


## + Generative adversarial network (GAN)
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mofzVUHRGJS6ocZy3k5EH_z0QHkAKXOe) Basic GAN for Digits Generation using MNIST

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1VtM1MZSrTawdeUon-dijO0X8z6Cgs_b5) DCGAN for Digits Generation using MNIST

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1tM0cMxPcVd0kwaF95tOqGqDZI-S4xZ2a) SN-GAN for Digits Generation using MNISTpara generar dígitos de MNIST

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1sxt4-I5DziPJ3pc7YaSNJUxABQ6WGyjq) WGAN-GP for Digits Generation using MNIST para generar dígitos de MNIST

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1EXTVpIqE66Q5N09V6bMx7X_he0PureuU) DCGAN for Generation of X-ray images of Shuriken (64x64 pixeles)



## + Anomaly Detection
* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1b5qUxqcy7q-_5fLS8S8jWUaO9oTqfDfv) Anomaly Detection using MNIST(0: normal class, 1,2,..9:anomaly) 

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OzyFFMCKUv_RrLvumExFIufV9qBx7TSy) Contrastive Learning in CIFAR dataset 

