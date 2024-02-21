# Brain-tumor-classification

**Project Overview**

This project explores the application of Convolutional Neural Networks (CNNs) for the classification of brain tumors from Magnetic Resonance Imaging (MRI) scans. Our goal is to leverage neural network capabilities to improve the accuracy of brain tumor classification, focusing on the impact of image quality on classification results.

**Authors:**

Milena Biernacka,
Agata Dratwa,
Patrycja Lewczuk,
Kornelia Susz.

**Dataset**

We utilized the Brain Tumor Classification MRI Dataset from Kaggle , comprising images categorized into glioma, meningioma, pituitary tumors, and no tumor, with a balanced distribution across classes. [Dataset](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri?fbclid=IwAR1jifRrna5JdMzLh4ifE56-mU8pwP9QSf3MQFa2d0CADGfqpcuj7EgTffE)

**Methods**

Our approach includes multilabel and binary classification on original and modified datasets. We investigate the robustness of CNNs against variations in image quality by applying Gaussian blur and resolution modifications to simulate different levels of image clarity.

**Results**

Our findings highlight the CNN's efficacy in classifying brain tumors with considerations for image quality variations. The binary classification model showed high accuracy (90%), while multilabel classification also demonstrated robust performance.

**Discussion**

The study underlines the potential of CNNs in medical imaging, emphasizing the need for high-quality imaging and the model's resilience to variations in image quality. Future research directions include exploring diverse neural network architectures and expanding dataset diversity.
