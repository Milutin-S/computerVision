# Image compression 

## Image compression using PCA (Principal Component Analysis) in Python

|The main package that we gona use is scikit-learn.
The basic idea of PCA is dimensionality reduction.

2D - 1D

The line that preserves the most of the variance possible
If you want a second line you would use a line that is orthogonal or perpedincular, 90 defrees to our first line and also that preserves the most of the variance.

To summerise, if we have N dimensional space, PCA will find the K dimensional space (K < N) that still preserves the most features of our inital data. 