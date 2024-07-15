# Email Spam Classifier

This project involves building and evaluating various machine learning models to classify emails as spam or not spam. The classifier has been trained on a dataset of emails, using algorithms such as Naive Bayes, Decision Trees, and K-Nearest Neighbors, achieving high accuracy in detecting spam emails.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Models Evaluated](#models-evaluated)
- [Results](#results)
- [Contributing](#contributing)

## Overview

The email spam classifier is designed to help identify unwanted spam emails using machine learning techniques. This project compares several classification models and selects the best-performing one based on accuracy and other performance metrics.

## Features

- Preprocessing of email text data
- Implementation of various machine learning algorithms
- Comparison and evaluation of model performance
- High accuracy in spam detection

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/vishalvky007/email_spam_classifier.git
    ```

2. Navigate to the project directory:
    ```sh
    cd email_spam_classifier
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Preprocess the email dataset:
    ```sh
    python preprocess.py
    ```

2. Train the classifier:
    ```sh
    python train.py
    ```

3. Evaluate the model:
    ```sh
    python evaluate.py
    ```

4. Classify new emails:
    ```sh
    python classify.py --email "your_email_here"
    ```

## Models Evaluated

- Naive Bayes
- Decision Trees
- K-Nearest Neighbors

## Results

The best-performing model achieved an accuracy of over 96% in classifying emails as spam or not spam. Detailed results and comparisons are provided in the `results` directory.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.
