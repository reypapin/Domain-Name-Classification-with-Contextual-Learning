Domain Name Classification with Contextual Learning

This repository contains code for training models to classify domain names into two categories: Domain Generation Algorithms (DGAs) and normal domain names, using contextual learning techniques. Python is the primary programming language used for development.
Introduction

Domain names play a crucial role in various internet-related applications. However, distinguishing between legitimate domain names and those generated by malicious algorithms (DGAs) can be challenging. This repository addresses this challenge by leveraging contextual learning methods to develop accurate classifiers.
Models

The primary models trained in this repository are Language Models (LMs), particularly Large Language Models (LLMs), such as LLama 3 8B. These models are trained on large datasets of domain names to learn contextual representations and patterns that distinguish between DGA-generated and normal domain names.
Usage

To use the models trained in this repository:

    Clone the repository to your local machine.
    Install the necessary dependencies listed in requirements.txt.
    Use the provided scripts or notebooks to train new models or evaluate existing ones.
    Experiment with different hyperparameters, architectures, and training techniques to improve model performance.
    Integrate the trained models into your applications for domain name classification tasks.

Repository Structure

    data/: Contains datasets used for training and evaluation.
    models/: Includes trained model checkpoints and configurations.
    scripts/: Contains utility scripts for data preprocessing, training, and evaluation.
    notebooks/: Jupyter notebooks demonstrating model training and evaluation workflows.

Contributing

Contributions to this repository are welcome! If you have ideas for improvements, new features, or bug fixes, feel free to open an issue or submit a pull request.

