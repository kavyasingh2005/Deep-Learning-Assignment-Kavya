# Deep Learning Assignment – Kavya Singh

This repository contains two Google Colab notebooks implemented as part of the Deep Learning assignment:

### 1️⃣ CNN Notebook  
**File:** `CNN.ipynb`  
**Description:**  
- Implements Convolutional Neural Network for image classification.
- Dataset is loaded directly from Google Drive. 
- Includes data preprocessing, model building, training, evaluation, and final outputs.

### 2️⃣ RNN Notebook  
**File:** `RNN.ipynb`  
**Description:**  
- Implements a Recurrent Neural Network (LSTM-based) for Twitter Sentiment Analysis.  
- Dataset is loaded directly from Google Drive.  
- Includes preprocessing, tokenization, model building, training, and evaluation.

## Dataset Information

The datasets used in these notebooks are **not uploaded** to this repository due to size limitations.  
Instead, they are loaded directly from Google Drive using:

```python
from google.colab import drive
drive.mount('/content/drive')
