# spokendigit-models

This project builds a variety of models for identifying spoken Arabic digits. The data used are the time series of mel-frequency cepstral 
coefficients (MFCCs) corresponding to the digits, obtained from the 
[UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Spoken+Arabic+Digit). Gaussian Mixture Models (GMMs) are built based on both the 
k-means and expectation-maximization algorithms, making use of `sklearn` modules. Several different modeling choices were explored, including normalization and placing constraints on the GMM covariances. By running the cells in the `Testing Code` section of the Jupyter Notebook, the model can be built and tested according to these modeling choices. The PDF presentation provides explanations and results from the various methods.
