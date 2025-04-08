# BrainTumourAI

This project involves building and evaluating a deep learning model to detect brain tumours from MRI scans using transfer learning techniques. The task was part of a deep learning coursework assignment, where models were trained and tested in a Jupyter Notebook environment using Anaconda.

## Overview

- **Models Used**:  
  - Transfer learning with **VGG16** as a base model  
  - Transfer learning with **EfficientNetB0** as a base model  
- **Architecture**:  
  Each pre-trained model is followed by a custom classifier tailored for binary classification (tumour vs. no tumour).
- **Environment**:  
  Anaconda (Python verion) and Jupyter Notebook

## Contents

- `Brain-Tumour-Detection.ipynb` – Jupyter notebook containing model code and evaluation
- `report.pdf` – Coursework report detailing methods, experiments, and results
- `requirements.txt` – List of dependencies to recreate the environment
- `brain_tumour_dataset` - Folder containing the MRI scans

## Getting Started

### Prerequisites

Make sure you have the following installed, anaconda should have the other necessary tools preinstalled, google colab also:

- Tensorflow 2.10.0
- Keras 2.10.0
- Python (3.9+)
- git

### Clone the Repository

```bash
git clone https://github.com/EliotDe/BrainTumourAI.git
cd BrainTumourAI
```

### Setting Up Your Environment

#### If using **Anaconda Navigator (Graphical UI)**:

1. Open **Anaconda Navigator**
2. Click on **"Environments"** on the left panel
3. Click **"Create"** to make a new environment (e.g. name it `braintumourai`)
4. Set the Python version to **3.9**
5. After creation, click **"Play"** > **"Open Terminal"** in that environment
6. Continue with the instructions below to install dependencies and run the notebook

#### If using **Anaconda Prompt / Terminal**:

```bash
# Create the conda environment
conda create --name braintumourai python=3.9

# Activate the environment
conda activate braintumourai

# Navigate into the project folder if you're not already there
cd BrainTumourAI

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
```
## Disclaimer
Some of the hyperparameters may not be at the optimal setting in my notebook due to me experimenting with different values. I have documented the best values in my report and the best results for both of the models.




