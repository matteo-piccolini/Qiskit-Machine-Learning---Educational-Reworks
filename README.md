# Qiskit Machine Learning - Educational Reworks

This repository contains a collection of Jupyter Notebooks based on the official **[Qiskit Machine Learning Tutorials](https://qiskit-community.github.io/qiskit-machine-learning/tutorials/index.html)**.

The goal of this project is to study, reproduce, and rework the original tutorials for educational purposes, providing deeper insights into Quantum Machine Learning (QML) through practical examples and personal annotations.

---

## 📚 Current Notebooks

The following notebooks have been reworked so far. This list will be updated as the study progresses.

1.  **[Quantum Neural Networks](./Quantum%20Neural%20Networks.ipynb)**
    * **Description**: Exploration of fundamental Quantum Neural Network (QNN) architectures. It covers the implementation of `EstimatorQNN` and `SamplerQNN`, analyzing how parameterized quantum circuits function as neural network layers.
    * **Original Tutorial**: [01_neural_networks](https://qiskit-community.github.io/qiskit-machine-learning/tutorials/01_neural_networks.html)

2.  **[Neural Network Classifier & Regressor](./Neural%20Network%20Classifier%20&%20Regressor.ipynb)**
    * **Description**: Practical application of QNNs for classification and regression tasks. It utilizes `VQC` (Variational Quantum Classifier) and `VQR` (Variational Quantum Regressor) on synthetic datasets to visualize the learning capabilities of quantum models.
    * **Original Tutorial**: [02_neural_network_classifier_and_regressor](https://qiskit-community.github.io/qiskit-machine-learning/tutorials/02_neural_network_classifier_and_regressor.html)

3.  **[Training a Quantum Model on a Real Dataset](./Training%20a%20Quantum%20Model%20on%20a%20Real%20Dataset.ipynb)**
    * **Description**: Application of the `VQC` to the **Iris flower dataset**. This notebook demonstrates the end-to-end pipeline: data preprocessing (PCA, Scaling), quantum feature mapping, and model training/evaluation on a real-world classification task.
    * **Original Tutorial**: [02a_training_a_quantum_model_on_a_real_dataset](https://qiskit-community.github.io/qiskit-machine-learning/tutorials/02a_training_a_quantum_model_on_a_real_dataset.html)

---

## ⚖️ Legal Notice & Licensing

This project contains code derived from the official Qiskit tutorials, which are property of IBM.

* **Original Copyright**: © Copyright IBM 2017, 2025.
* **License**: The original code is licensed under the **Apache License, Version 2.0**. You may obtain a copy of the license in the [LICENSE.txt](./LICENSE.txt) file in this repository or at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0).

### Modifications
In compliance with the Apache 2.0 License:
* Each reworked notebook includes a notice identifying it as a **personal reproduction and rework** of the original Qiskit tutorials.
* Modifications (such as additional comments, code restructuring, or visualization changes) have been made for educational and study purposes.
* All original copyright notices from IBM have been preserved within the individual files.

---

## 🛠️ Requirements

To run these notebooks, ensure you have the latest version of Qiskit and the Machine Learning module installed:

```bash
pip install qiskit qiskit-machine-learning qiskit-aer scikit-learn seaborn matplotlib
