# TumorSense: Brain Tumor Detection Project

## Overview
TumorSense is a machine learning project aimed at automating brain tumor detection from medical images using Machine Learning and Deep Learning techniques. Leveraging image classification techniques, the project determines whether an input image contains a brain tumor or not. This solution holds potential to assist medical professionals in swift and accurate preliminary diagnosis.

The repo contains 2 colab files, wherein:
1. Compares and contrasts SVM and LR (for my MPR)
2. Used ML and DL for comparison purposes.(This notebook is exhaustive and is created for a comparative study)

## Author
- Sarah Pendhari

# Brain Tumor Detection Models Overview

## Introduction
Brain tumors pose significant health challenges, requiring accurate detection methods for timely intervention. This document outlines the models utilized for brain tumor detection and their significance.

## Models Used
1. **VGG-16 Algorithm**:
   - **Description**: VGG-16 is a Convolutional Neural Network (CNN) model comprising 16 layers, initially trained on the ImageNet dataset.
   - **Significance**: It has demonstrated effectiveness in various computer vision tasks, including image classification and object recognition. In the context of brain tumor detection, VGG-16's ability to identify intricate features within images facilitates precise categorization.
   - **Application**: Trained on a dataset containing brain tumor images, VGG-16 enhances its capability to accurately classify such images, thereby improving detection accuracy.

2. **VGG-19 Algorithm**:
   - **Description**: VGG-19 is an extension of VGG-16, featuring 19 layers. It retains the architecture principles of its predecessor while adding more layers.
   - **Significance**: VGG-19 offers a deeper architecture compared to VGG-16, potentially capturing more complex features in brain tumor images.
   - **Application**: Similar to VGG-16, VGG-19 is trained on brain tumor image datasets to assess its effectiveness in detection and classification tasks.

3. **InceptionV3**:
   - **Description**: InceptionV3 is a CNN model, notable for its inception modules, allowing for efficient use of computational resources.
   - **Significance**: It has been widely utilized in various image-related tasks due to its efficient architecture. In the context of brain tumor detection, InceptionV3's performance is evaluated to determine its suitability compared to other models.
   - **Application**: InceptionV3 is included in the study to compare its performance with VGG-16, VGG-19, and other models, contributing to the development of an optimal brain tumor detection model.

4. **ResNet50**:
   - **Description**: ResNet50 is a CNN model characterized by residual connections, enabling the training of very deep networks.
   - **Significance**: ResNet50 addresses the vanishing gradient problem in deep neural networks, allowing for the successful training of deeper architectures.
   - **Application**: ResNet50's performance is evaluated alongside other models to assess its effectiveness in brain tumor detection tasks.

5. **MobileNet**:
   - **Description**: MobileNet is a lightweight CNN model designed for mobile and embedded vision applications, characterized by its efficient architecture.
   - **Significance**: MobileNet offers a balance between model size and accuracy, making it suitable for resource-constrained environments.
   - **Application**: MobileNet's performance is assessed in the context of brain tumor detection, evaluating its effectiveness compared to more complex models like VGG-16, VGG-19, InceptionV3, and ResNet50.

## Conclusion
The selection of appropriate models is crucial for enhancing the accuracy and effectiveness of brain tumor detection algorithms. By comparing VGG-16, VGG-19, InceptionV3, ResNet50, and MobileNet, this study aims to contribute to the development of efficient models for identifying brain tumors, ultimately improving patient outcomes.


## Usage
To run the project:
1. Clone the repository: `git clone https://github.com/SarahPendhari/TumorSense.git`
2. Install required dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebooks in `notebooks/` for SVM and LR training and classification.
4. Navigate to the `webapp/` directory and launch the user interface.

## Contribution
Contributions to TumorSense are welcome! If you'd like to enhance the project, follow these steps:
1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Make your modifications and commit changes: `git commit -m "Add feature"`.
4. Push to your fork: `git push origin feature-name`.
5. Open a pull request detailing your changes.

## Acknowledgments
Special thanks to the creators of the dataset used for training and testing. This project would not be possible without their contribution.

## License
This project is licensed under the MIT License. Feel free to modify and use it according to your needs.

---

📌 Explore the codebase, contribute, and help us bring accurate brain tumor detection one step closer with TumorSense!

