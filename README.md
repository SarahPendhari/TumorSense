# TumorSense: Brain Tumor Classification Project

## Overview
TumorSense is a machine learning project aimed at automating brain tumor detection from medical images using Support Vector Machines (SVM) and Logistic Regression (LR). Leveraging image classification techniques, the project determines whether an input image contains a brain tumor or not. This solution holds potential to assist medical professionals in swift and accurate preliminary diagnosis.

## Authors
- Sarah Pendhari
- Karan Pashte

## SVM and LR
- **Support Vector Machines (SVM)**: SVM is a powerful supervised learning algorithm used for classification and regression tasks. In TumorSense, SVM is utilized to create a decision boundary that maximizes the separation between tumor and non-tumor image data, enabling accurate classification.

- **Logistic Regression (LR)**: Despite its name, LR is a widely-used classification algorithm. It estimates the probability of a binary outcome (e.g., tumor or non-tumor) based on input features. In TumorSense, LR serves as a benchmark model for comparison with SVM's classification performance.

## Features
- Utilizes SVM and LR for binary classification.
- Processes medical images to extract relevant features.
- Provides a user-friendly interface for uploading and analyzing images.
- Generates classification results with confidence scores.

## Project Structure
The project repository is organized as follows:

- `data/`: Contains the dataset used for training and testing.
- `notebooks/`: Jupyter notebooks detailing the SVM and LR training and image classification process.
- `src/`: Python scripts for image preprocessing, SVM and LR model creation, and classification.
- `webapp/`: Front-end code for the user interface to upload and analyze images.
- `docs/`: Documentation files providing insights into the project and its components.

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

