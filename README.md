# DATA2060-Final-Project
Final Project for DATA2060 course.

In this project, Zachk Huang and Zixi (Valerie) Li implement Gaussian Naive Bayes (GNB) from scratch, reproduce scikit-learn results, and document the mathematical foundations and numerical algorithms used.

## Authors

Zachk Huang, Dept. of Sociology & Data Science Institute, Brown University. Email: yifei_huang1@brown.edu

Zixi (Valerie) Li, Dept. of Sociology, Brown University. Email: zixi_li1@brown.edu

## Python and Package Versions

See `data2060.yml`.

## Project Summary
Gaussian Naive Bayes is a simple probabilistic classifier that assumes:
- Features are independent given the class
- Each feature follows a Gaussian distribution within each class
- Predictions are made by choosing the class with the largest posterior probability

In this project, we:
- Implement GNB manually (priors, means, variances, log-likelihoods)
- Train and evaluate it on the Iris dataset
- Compare outputs against scikit-learn
- Visualize confusion matrices and Gaussian density curves
- Document the math using Markdown + LaTeX

## Key Results
- Custom GNB accuracy: 0.967
- sklearn GNB accuracy: 0.967
- Predictions: 100% identical between the two models.
