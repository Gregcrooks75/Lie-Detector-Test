## Project Summary

This project explores the use of Convolutional Neural Networks (CNN) for detecting concealed information ("lying") in the realm of computational psychology. The research compared a linear (Logistic Regression) and non-linear (CNN) machine learning model using data from Wiese et al (2021). The data represented neuronal activity of participants exposed to familiar or unfamiliar faces, with their truthful or untruthful responses recorded.

The Python-based analysis involved data cleaning, downsampling, pre-processing using a standard scaler, creating train-test subsets, and defining target outputs: 0 for truthful unfamiliarity, 1 for untruthful responses, and 2 for truthful familiarity.

Predictions were made using Logistic Regression and four different CNN architectures, assessed through confusion matrices and accuracy scores. Results revealed higher prediction accuracy for all CNN architectures, though with a noted imbalance in predictions at the 50-55% mark. Future work could involve testing other machine learning models or incorporating additional data to address these issues.
