# Flood_Susceptibility_Modeling
Flood susceptibility modeling and risk assessment using multi-class classification, data augmentation, and explainable AI (XAI).

# Overview
This repository contains code for three main components of the flood risk analysis project:

1. Data Augmentation: This part addresses the issue of class imbalance in multi-class flood susceptibility mapping (FSM). The data augmentation methods are designed to generate synthetic samples that help balance the distribution of classes, enabling a more accurate and robust flood risk assessment.

2. Model Training and Robustness Testing: This section involves the training and robustness evaluation of models. Specifically, the XGBoost ensemble model is used as the meta-model in pre-experiments. For deep learning experiments, the LSTM (Long Short-Term Memory) model requires setting up an environment with PyTorch or TensorFlow. Note that running these models has high time and hardware requirements due to their complexity. Therefore, sufficient hardware resources and software environments must be configured before running the code.

3. Explainable AI (XAI) for Knowledge Discovery: This component focuses on applying XAI methods to enhance the interpretability of models, allowing for better understanding and transparency of decision-making. The goal is to reveal the key factors driving flood risk predictions at various severity levels.

# Data
Due to the sensitive nature of emergency management data, we are unable to provide real-world datasets directly. However, if you need access to the data for further experiments or research, please contact us via email, and we will provide you with encoded data. Alternatively, you can use open-source emergency management datasets or other domain-specific datasets for testing and training.

# Setup Instructions
1. Dependencies:
    - For LSTM model training, ensure that you have PyTorch or TensorFlow installed in your environment. You can install them via:
      pip install torch  # For PyTorch
      pip install tensorflow  # For TensorFlow

2. Hardware Requirements: Due to the heavy computational needs of the models, especially deep learning models like LSTM, it is recommended to use a machine with a GPU for faster training times.

# Contact
If you require access to the sensitive dataset or have any questions, feel free to reach out to us by email.
