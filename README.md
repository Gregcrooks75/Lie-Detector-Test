# Dissertation-Code

## Summary

This report studies the use of Convolutional Neural Networks (CNN) as a classifier to detect
concealed information (“lying”). The concept or Neural Network constitutes a state of the art tool,
which holds interesting prospects in the field of computational psychology. As such, my project
sought to fill in the gap in contemporary research by comparing a linear (Logistic Regression) to
non-linear (CNN) Machine Learning models. To do so, I extracted data from Wiese et al
(2021), which showed neuronal activity of 19 participants after being shown familiar or
unfamiliar faces over 25 to 40 trials; each lasting 1 second. In the experiment, participants were
either truthful or untruthful about their familiarity or unfamiliarity. To perform my analysis, I
used Python. Firstly, I cleaned our data by downsampling our dataset, then pre-processed our
data by using a standard scaler, creating train-test subsets and establishing target outputs: 0 for
truthful unfamiliarity (Unfamiliar), 1 for untruthful familiarity or unfamiliarity (Lying), 2 for truthful
familiarity (True). Subsequently, I predicted on my testing sets using Logistic Regression
models and 4 different CNN architectures, then used confusion matrices and accuracy scores
as metrics. As a result, I found that all CNN architectures have a better accuracy prediction on
our data but that issues of arbitrary imbalance between predictions were arising at the 50-55%
mark. Conclusively, it would be relevant to test other Machine Learning models or gather
additional data for prospective research in order to amend this issue.
