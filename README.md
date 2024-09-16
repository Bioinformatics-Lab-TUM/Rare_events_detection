# Rare Events Detection and Forecasting in Dynamic Systems

This repository contains the implementation of a machine learning-based pipeline for detecting and forecasting rare events in dynamic systems, specifically focusing on the banking sector. Rare events, such as financial crises, banking failures, and epidemics, can have severe impacts, making early detection essential for mitigating financial losses and ensuring operational stability. Our approach combines advanced feature selection techniques with Support Vector Machines (SVMs) and probabilistic models to deliver high accuracy and robustness.

## Key Features:
- **Rare Event Detection**: Designed for predicting rare, high-impact events in dynamic systems using heterogeneous data sources.
- **Advanced Feature Selection**: Utilizes **Wavelet Transform** for multi-scale analysis and **Fenchel Transform** to extract meaningful patterns from log and transaction data.
- **SVM with Multiple Kernels**: Implements SVMs with linear, polynomial, radial basis function (RBF), and sigmoid kernels to capture diverse data characteristics.
- **Balanced Data Training**: Incorporates **SMOTE** oversampling and undersampling strategies to ensure training on balanced data, reducing overfitting.
- **Probabilistic Model Integration**: Uses **Binary Logistic Regression** for post-processing the outputs from SVM classifiers to make the final predictions.

## Application in the Banking System:
The pipeline is validated using publicly available logs from the **Loghub** dataset, sourced from lab servers in a banking system environment. This dataset includes operations logs, transaction data, and system performance metrics, making it a suitable real-world scenario for rare event detection and forecasting.

## Performance Metrics:
- **Precision**: 94%
- **Recall**: 92%
- **Mean Squared Error (MSE)**: 0.03
- **Overall Accuracy**: 96%

These results highlight the pipeline's effectiveness in predicting rare events, showcasing its robustness and predictive accuracy in dynamic systems.

## References:
1. A Systematic Review of Rare Events Detection Across Modalities using Machine Learning and Deep Learning. [https://www.techrxiv.org/users/693917/articles/683317-a-systematic-review-of-rare-events-detection-across-modalities-using-machine-learning-and-deep-learning](https://www.techrxiv.org/users/693917/articles/683317-a-systematic-review-of-rare-events-detection-across-modalities-using-machine-learning-and-deep-learning).
2. He, S. et al. (2008). Loghub: A Large Collection of System Log Datasets for AI-driven Log Analytics. [https://arxiv.org/abs/2008.06448](https://arxiv.org/abs/2008.06448).
3. Cristianini, N. & Ricci, E. (2008). Support Vector Machines. In **Encyclopedia of Algorithms**, 928–932. Springer US, Boston, MA. DOI: [10.1007/978-0-387-30162-4_415](https://doi.org/10.1007/978-0-387-30162-4_415).

## Authors:
- **Eugeniu Catlabuga**, **Nicolae Drabcinschi**, **Viorel Munteanu**, **Viorica Sudacevschi**  
  Technical University of Moldova
