# Prediction of Gestational Age from MRI Data

## Project Overview
This project applies deep learning techniques to predict the gestational age at scan and at birth of neonates, using data from the Developing Human Connectome Project (dHCP). The task leverages cortical thickness, cortical curvature, cortical myelination, and sulcal depth metrics derived from MRI scans to create a predictive model using a custom ResNet architecture.

## Key Objectives
- **Data Handling**: Create custom PyTorch `DataSets` and use `DataLoader` for sampling batches.
- **Data Augmentation**: Implement augmentation strategies to enhance model performance.
- **Model Architecture**: Develop a custom ResNet with preactivation for regression tasks.
- **Training**: Execute a robust training loop with optimization.
- **Visualization**: Analyze the network's outputs to ensure it learns relevant features.

## Methodology
The approach involves:
- **Preprocessing and Data Augmentation**: Preparing the MRI data and applying transformations to improve generalization.
- **Custom ResNet Design**: Tailoring a ResNet architecture specifically for this regression task.
- **Optimization and Training**: Detailed setup of the training phases, including loss function selection and optimizer tuning.
- **Results Visualization**: Evaluating the model's performance through visual analysis of its predictions versus ground truth.

## Results
Detailed visualization and analysis of model predictions are provided in the Jupyter Notebook, showcasing the effectiveness of the deep learning model in predicting neonatal gestational ages.
