# Alzheimer's Disease Detection using MRI Scans
Improving the accuracy of Alzheimer's Disease Detection is achieved through the utilization of Convolutional Autoencoder architecture, providing enhanced capabilities in feature representation and extraction. This, in turn, contributes to the development of more precise and efficient diagnostic models.

## Motivation 
Alzheimer's Disease Detection using MRI scans is a pressing concern underscored by compelling statistics. Approximately 50 million people worldwide are affected by Alzheimer's, and this number is anticipated to triple by 2050. Moreover, Alzheimer's constitutes 60-70% of dementia cases, establishing itself as the most prevalent form of dementia. The scale of the issue emphasizes the critical need for accurate and timely diagnostic methods.

Early detection is crucial, given that up to 70% of Alzheimer's cases remain undiagnosed in the early stages. The implications of delayed identification are significant, as early diagnosis not only improves patient outcomes but also facilitates the implementation of interventions that may slow the progression of the disease. With the rising global impact and increasing prevalence of Alzheimer's, advancing detection methods becomes imperative, particularly through the integration of advanced technologies such as MRI scans.

In light of the substantial global impact and the escalating prevalence of Alzheimer's, the development and refinement of detection methods are vital for effective disease management and healthcare planning. The utilization of advanced technologies, exemplified by MRI scans, presents a promising avenue to enhance the precision and efficiency of Alzheimer's Disease Detection, ultimately contributing to improved patient care and public health initiatives.

## Dataset
The dataset consists of 5 stages of Alzheimer's Disease already split into two directories for training and testing: EMCI, LMCI, MCI, AD, CN.
<br>
The dataset can be found [here](https://www.kaggle.com/datasets/madhucharan/alzheimersdisease5classdatasetadni).

## Proposed Architecture

<img src="https://github.com/mohd-raza/EADDA-Towards-Novel-Explainable-Deep-Learning-for-Alzheimer-s-Disease-Diagnosis-Using-Autoencoders/assets/91888013/651ab47c-59e4-4b60-86d8-c440a946349e" alt="image" width="700" height="500">

## Results
<img src="https://github.com/mohd-raza/EADDA-Towards-Novel-Explainable-Deep-Learning-for-Alzheimer-s-Disease-Diagnosis-Using-Autoencoders/assets/91888013/6e41af5f-e0be-407a-9694-6077ba0c48ff" alt="image" width="550" height="400">


The paper proposes a novel deep learning system called EADDA for early Alzheimer's disease diagnosis using MRI images. The system uses a convolutional autoencoder for dimensionality reduction and feature extraction from the MRI images. The encoded features are fed into an ensemble classifier module containing SVM, Random Forest, Extra Trees, XGBoost, and MLP classifiers. The model is trained and tested on the 5-class ADNI dataset with 1296 MRI images across 5 classes.

The proposed EADDA system achieves an overall accuracy of 86.57% outperforming several pretrained CNN models like MobileNet, ResNet50, and VGG19. It also outperforms other existing methods on the ADNI dataset. The convolutional autoencoder with 4 encoding and 4 decoding layers provides the best performance. Among the classifiers, Extra Trees yields the highest accuracy of 86.57%. The results demonstrate the effectiveness of the proposed autoencoder and ensemble classifier based approach for early Alzheimer's diagnosis using brain MRI images. The model shows promise for improving reliability and early detection of Alzheimer's disease.

## Publication
Our research work, titled [**EADDA: Towards Novel and Explainable Deep Learning for Early Alzheimer's Disease Diagnosis Using Autoencoders**](https://ijisae.org/index.php/IJISAE/article/view/3517) has been published in the ***Scopus Indexed Journal, "International Journal of Intelligent Systems and Applications in Engineering (ISSN:2147-6799) (2023).***
## Authors: 
Mohammed Raza Syed, Neel Kothari, Yash Joshi & Dr. Aruna Gawade
