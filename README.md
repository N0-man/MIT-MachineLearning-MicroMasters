# Students Notes from MITx 6.86x semister

Machine Learning with Python: from Linear Models to Deep Learning

**Disclaimer**: The following notes are a mesh of my own notes, forums, youtube, copilot, some useful forum threads and various course material. There may be various error and that could very well be due to my own interpretation during learning. If you spot an error, want to specify something in a better way (English is not my primary language), add material or just have comments, you can clone, make your edits and make a pull request (preferred) or just open an issue.

### Context (2024)

Machine learning methods are commonly used across engineering and sciences, from computer systems to physics. Moreover, commercial sites such as search engines, recommender systems (e.g., Netflix, Amazon), advertisers, and financial institutions employ machine learning algorithms for content recommendation, predicting customer behavior, compliance, or risk.

As a discipline, machine learning tries to design and understand computer programs that learn from experience for the purpose of prediction or control.

In this course, you will learn about principles and algorithms for turning training data into effective automated predictions. We will cover:

- Representation, over-fitting, regularization, generalization, VC dimension;
- Clustering, classification, recommender problems, probabilistic modeling, reinforcement learning;
- On-line algorithms, support vector machines, and neural networks/deep learning.

The objective is to learn

1. Understand principles behind machine learning problems such as classification, regression, clustering, and reinforcement learning
2. Implement and analyze models such as linear models, kernel machines, neural networks, and graphical models
3. Choose suitable models for different applications
4. Implement and organize machine learning projects, from training, validation, parameter tuning, to feature engineering

### Build Jupiter Book

Install ghp-import

```
pip install ghp-import
```

Build Jupiter Book

```
jb build .
```

From the main branch of your book’s root directory (which should contain the \_build/html folder) call ghp-import and point it to your HTML files

```
ghp-import -n -p -f _build/html
```

> :warning: …ghp-import will DESTROY your gh-pages branch… and assumes that the gh-pages branch is 100% derivative. You should never edit files in your gh-pages branch by hand if you’re using this script…

Your book is available on
https://N0-man.github.io/MIT-MachineLearning-MicroMasters/
