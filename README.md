# Age and Gender Prediciton

The project aims to develop a gender and age detector using deep learning techniques, specifically Convolutional Neural Networks (CNNs). The detector will analyze images of faces and classify them into one of two genders (Male/Female) and one of eight age ranges. The project utilizes pre-trained models developed by Tal Hassner and Gil Levi, trained on the Adience dataset, which is publicly available and covers various real-world imaging conditions.

# Project Overview

- Project Objective: Utilize deep learning techniques to accurately predict the gender and age of individuals from single face images.
- Model Source: Leveraging pre-trained models by Tal Hassner and Gil Levi, specifically designed for gender and age estimation.
- Gender and Age Prediction: Gender classification includes 'Male' or 'Female', while age falls into eight ranges (0 – 2, 4 – 6, 8 – 12, 15 – 20, 25 – 32, 38 – 43, 48 – 53, 60 – 100).
- Dataset: Employing the Adience dataset, a comprehensive benchmark for face photos, to train our models, considering its inclusivity of real-world imaging conditions.
- CNN Architecture: The convolutional neural network comprises three layers with varying numbers of nodes and kernel sizes, followed by two fully connected layers and a softmax output layer.
- Process: Automated age and gender estimation involves face detection, tracking, feature extraction, and utilization of these features for accurate gender and age classification.

# Machine Learning Models Used:

- Face Detection Module: This module is responsible for detecting faces within an image. Techniques such as Haar cascades or more advanced methods like CNN-based face detection can be employed for this purpose.

- Gender and Age Classification Module: This module utilizes CNNs to classify detected faces into genders (Male/Female) and age ranges. The CNN architecture consists of three convolutional layers followed by two fully connected layers and a final output layer with softmax activation.

# Conclusion:

The project's scope includes applications in security-based systems, medical fields, and any scenario requiring automated age and gender detection from images. It is feasible, affordable, and leverages data analytics to provide accurate predictions. By breaking down the system into two modules, face detection and age/gender classification, the implementation is simplified, enhancing its practicality and usability.

# NOTE:- Large Files Download
Due to size restrictions on GitHub, we couldn't include some large files in this repository. You can download these files using the link below:
- [age_net.caffemodel](https://drive.google.com/file/d/1rttkQMi6vNaiDpUqXzMBpJ9fZdHSPjzs/view?usp=drive_link)
- [gender_net.caffemodel](https://drive.google.com/file/d/1RRP22trTOIKcbJ9oHpUoM_30dGmiLcc9/view?usp=sharing)

To access the files, click on the respective "Download File" links above. If prompted, select the option to download the files to your device.
