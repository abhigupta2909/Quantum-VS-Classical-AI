# Quantum vs. Classical ML: A Performance Showdown

## Project Overview

This project explores and compares the performance of machine learning algorithms executed on classical and quantum computers. The purpose of this research is to investigate whether quantum computing offers any performance benefits in terms of accuracy and execution time over traditional classical machine learning approaches.

## Motivation

Quantum computing is often touted for its potential to solve complex problems more efficiently than classical computing. With the growing interest in applying quantum algorithms to various fields, including machine learning, this project aims to provide empirical evidence of the strengths and limitations of quantum machine learning compared to classical methods.

## Key Findings

- **Quantum Variational SVM**: Outperformed classical SVM in terms of accuracy on multi-class classification problems.
- **Quantum Kernel-Based SVM**: Showed mixed results, with higher accuracy in some cases but no significant speedup in execution time.
- **Classical SVM**: Remained competitive, especially in binary classification tasks, highlighting that quantum advantages are not yet fully realized in all scenarios.

## Technologies Used

- **Quantum Computing Platforms**: IBM Quantum Experience, Qiskit Aqua
- **Classical Computing Tools**: Python, Scikit-learn
- **Datasets**: UCI ML Breast Cancer Wisconsin (Diagnostic), UCI ML Wine Dataset

## Presentation

[View the Presentation](https://drive.google.com/file/d/1GMWgnAM39eY91mODDHruNFmRQNmg0Oz9/view?usp=sharing)

[embed]https://drive.google.com/file/d/1GMWgnAM39eY91mODDHruNFmRQNmq00z9/view?usp=sharing[/embed]

## Structure of the Project

1. **Introduction**: Background on quantum computing and its potential in machine learning.
2. **Classical vs Quantum Machine Learning**: Detailed comparison of classical and quantum algorithms.
3. **Experiments and Methods**: Description of datasets, algorithms used, and the experimental setup.
4. **Results**: Analysis of the performance metrics for both classical and quantum approaches.
5. **Conclusion**: Summary of findings and discussion on the future of quantum machine learning.

## Getting Started

To reproduce the experiments in this project, you will need to set up the following environment:

### Prerequisites

- Python 3.x
- Qiskit Aqua
- Scikit-learn
- IBM Quantum Experience account (for accessing quantum computers)

### Running the Experiments

To run the experiments, execute the Jupyter notebooks provided in the `notebooks` directory. Ensure that you have configured your IBM Quantum Experience API token for accessing quantum resources.

## QML Model
![Model Training Details](https://github.com/user-attachments/assets/6ac1cc08-7e3a-433b-8e66-4bc930e7c10a)


## Findings
![Fig: Final Analysis](https://github.com/user-attachments/assets/dce69065-d277-4b7b-a5aa-018e86862fed)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## References

- [Quantum Machine Learning: What Quantum Computing Means to Data Mining](https://example.com)
- [Supervised Learning with Quantum Enhanced Feature Spaces](https://example.com)
- [Quantum convolutional neural networks](https://arxiv.org/abs/1810.03787), Authors: Iris Cong, Soonwon Choi, and Mikhail D. Lukin.
- [Training an Artificial Neural Network Using Qubits as Artificial Neurons: A Quantum Computing Approach](https://arxiv.org/abs/2001.04449), Authors: Avinash Chalumuria, Raghavendra Kuneb, B. S. Manoja.
- [Quantum Parallelism](https://www.sciencedirect.com/topics/engineering/quantum-parallelism), ScienceDirect.
- [Machine Learning on Encrypted Data](https://www.ericsson.com/en/blog/2021/9/machine-learning-on-encrypted-data), Ericsson.
- [Quantum of Encryption](https://www.hpe.com/us/en/insights/articles/quantum-of-encryption-1707.html), Hewlett Packard Enterprise.
- [How May Quantum Computing Benefit Machine Learning](https://towardsdatascience.com/how-may-quantum-computing-benefit-machine-learning-c96de0bef0d4), Towards Data Science.
- [Quantum Computing Parallelism](https://blogs.iu.edu/sciu/2019/07/13/quantum-computing-parallelism/), Indiana University Blogs.
- [Supervised Learning with Quantum Enhanced Feature Spaces](https://arxiv.org/abs/1802.06002), arXiv.
- [Single Qubit Gates](https://learn.qiskit.org/course/ch-states/single-qubit-gates#cnot), Qiskit Learning.
- [Quantum Neural Networks](https://www.ibm.com/blogs/research/2020/06/quantum-neural-networks/), IBM Research.
- [TensorFlow Beginner Quickstart](https://www.tensorflow.org/tutorials/quickstart/beginner), TensorFlow.
- [Exploring the Capabilities of Quantum Neural Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9016555&tag=1), IEEE Xplore.

