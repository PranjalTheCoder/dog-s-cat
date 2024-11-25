# DOG vs CAT Identifier

## Table of Contents
1. [Project Report](#project-report)
    - [Title](#title)
    - [Team Details](#team-details)
    - [Problem Statement](#problem-statement)
    - [Dataset Details](#dataset-details)
    - [Approach/Methodology](#approach-methodology)
    - [Result Analysis](#result-analysis)
2. [How to Run the Project](#how-to-run-the-project)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Execution](#execution)
3. [Folder Structure](#folder-structure)

---

## Project Report

### Title
**DOG vs CAT Identifier**

### Team Details
1. **Devesh** (2023CA33) - Data preprocessing and augmentation.
2. **Pranjal Tamrakar** (2023CA72) - Model architecture and training.
3. **Shivam Bhatnagar** (2023CA91) - Dataset collection and validation.
4. **Prateek Lahri** (2023CA73) - Result analysis and reporting.
5. **Shushant Sonwani** (2023CA) - Integration and testing.

### Problem Statement
Create a deep learning model to classify images of dogs and cats into their respective categories using a binary classification approach. This involves training a Convolutional Neural Network (CNN) on a dataset of labeled images.

### Dataset Details
- **Source**: [Cats and Dogs Filtered Dataset](https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip)
- **Features**: RGB images resized to (150x150).
- **Sample Size**:
  - Training samples: 2000 (1000 per class).
  - Validation samples: 1000 (500 per class).

### Approach/Methodology
1. **Preprocessing**: Images were normalized and augmented to improve generalization.
2. **Model Architecture**:
   - Convolutional layers for feature extraction.
   - Max-pooling layers for dimensionality reduction.
   - Dense layers for classification with a sigmoid activation function.
3. **Training**:
   - Optimizer: Adam.
   - Loss Function: Binary Crossentropy.
   - Metrics: Accuracy.
   - Epochs: 10.

### Result Analysis
- **Accuracy**: Achieved a training accuracy of ~90% and validation accuracy of ~87%.
- **Loss**: Minimal overfitting observed due to proper augmentation and regularization techniques.

---

## How to Run the Project

### Prerequisites
- Python 3.10+
- TensorFlow 2.17.1
- Matplotlib 3.8.0

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-repo>/dog-vs-cat-identifier.git
   cd dog-vs-cat-identifier
2. Install the required libraries:
  ```bash
    pip install tensorflow matplotlib
