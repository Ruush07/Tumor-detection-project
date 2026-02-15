# Brain Tumor Detection using CNN 🧠

## Project Overview
This project leverages **Deep Learning** and **Convolutional Neural Networks (CNNs)** to automate the detection of brain tumors from MRI scans. Developed as a mid-term PBL initiative, the goal is to assist medical professionals by providing a rapid, preliminary diagnostic tool.

## Key Features
* **Custom CNN Architecture**: A 3-layer convolutional network designed specifically for medical image feature extraction.
* **High Accuracy**: Utilizing binary classification to distinguish between 'Tumor' and 'Healthy' scans.
* **Data Augmentation**: implemented using `torchvision` to improve model generalization.

## Tech Stack
* **Language**: Python 3.x
* **Framework**: PyTorch
* **Dataset**: Brain MRI Images for Brain Tumor Detection (Navoneel)
* **Visualization**: Matplotlib

## How to Run
1.  Clone the repository:
    ```bash
    git clone [https://github.com/Ruush07/Tumor-detection-project.git](https://github.com/Ruush07/Tumor-detection-project.git)
    ```
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3.  Run the Jupyter Notebook `Brain_Tumor_Detection_Using_Pytorch.ipynb`.

## Results
The model achieves significant accuracy on the test set, demonstrating the capability of CNNs in medical imaging tasks. (See notebook for visualization grids).
