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

## Contributions

This project was conducted by Christopher Havenstein, Damarcus Thomas, and Swami Chandrasekaran as part of their research at Southern Methodist University.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## References

- [Quantum Machine Learning: What Quantum Computing Means to Data Mining](https://example.com)
- [Supervised Learning with Quantum Enhanced Feature Spaces](https://example.com)
