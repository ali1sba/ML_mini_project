# Mini Machine Learning Project: From Scratch

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python Version](https://img.shields.io/badge/python-3.8+-brightgreen.svg)

## Overview

This repository contains a mini machine learning project where three algorithms are implemented from scratch:

- **One Rule (OneR)**
- **k-Nearest Neighbors (k-NN)**
- **Naive Bayes**

The purpose of this project is to understand the foundational concepts of these algorithms by implementing them without using any external machine learning libraries.

## Table of Contents

- [Installation](#installation)
- [Project Structure](#project-structure)
- [Algorithms Implemented](#algorithms-implemented)
- [Contributing](#contributing)
- [License](#license)
- [Contact Information](#contact-information)

## Installation

To get started, clone the repository and install the dependencies:

```bash
git clone https://github.com/ali1sba/ML_mini_project.git
cd ML_mini_project
pip install -r requirements.txt
```
## Project Structure

```
.
├── dataset
│   └── raw_data.csv              # TODO
│   └── sample_submission.csv     # Sample submission data
│   └── test.csv                  # features related to patient, hospital. Need to predict the Length of stay for each case_id
│   └── train.csv                 # Features related to patient, hospital and Length of stay on case basis
│   └── train_data_dict.csv       # Information of the features in train file
├── KNN
|   ├── dataset
|   │   └── raw_test01.csv            # TODO
|   │   └── raw_train01.csv           # TODO
|   │   └── sample_submission.csv     # Sample submission data
|   │   └── test.csv                  # features related to patient, hospital. Need to predict the Length of stay for each case_id
|   │   └── train.csv                 # Features related to patient, hospital and Length of stay on case basis
|   │   └── train_data_dict.csv       # Information of the features in train file
|   ├── KNN.ipynb                 # k-Nearest Neighbors algorithm implementation
├── Naive Bayes
│   └── ML MINI PROJET CAT_VERSION.ipynb                # Naive Bayes algorithm implementation
│   └── train.csv                 # TODO
├── ONE RULE.ipynb                # One Rule algorithm implementation
├── README.md                     # This README file
└── requirements.txt              # TODO
```
## Algorithms Implemented

### One Rule (OneR)
A simple classification algorithm that creates a single rule based on one feature. The rule is selected by evaluating which single feature provides the highest accuracy.

### k-Nearest Neighbors (k-NN)
A non-parametric method used for classification and regression. It classifies data points based on the majority label of their k nearest neighbors in the feature space.

### Naive Bayes
A probabilistic classifier based on Bayes' theorem with strong (naive) independence assumptions between the features. Often used for text classification and spam filtering.

## Contributing
Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch ```git checkout -b feature/new-feature```
3. Commit your changes ```git commit -m 'Add new feature'```
4. Push to the branch ```git push origin feature/new-feature```
5. Open a Pull Request

## License
This project is licensed under the MIT License.

## Contact Information
For any questions or suggestions, please contact:

Email: [HARIRI Ali](mailto:a.hariri@esi-sba.dz?subject=[GitHub]%20Source%20ML%20MiniProjet)

GitHub: [ali1sba](https://github.com/ali1sba)
