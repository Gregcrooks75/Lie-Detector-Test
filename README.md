## Project Summary

This project delves into the realm of computational psychology, employing Convolutional Neural Networks (CNN) and Logistic Regression to detect concealed information, commonly referred to as "lying". Utilizing neuronal activity data from Wiese et al (2021), which encompasses responses to familiar and unfamiliar faces, this research juxtaposes linear and non-linear machine learning approaches in analyzing truthful and untruthful responses.

The methodology entailed comprehensive data preprocessing, including cleaning, downsampling, and standardization using a Standard Scaler. Training and testing datasets were methodically prepared, with target outputs labeled as 0 (truthful unfamiliarity), 1 (untruthful responses), and 2 (truthful familiarity).

The analysis, conducted using Python, evaluated the performance of Logistic Regression against four CNN architectures. Each model's efficacy was measured through confusion matrices and accuracy metrics. Notably, all CNN models surpassed Logistic Regression in prediction accuracy, though an imbalance in predictions was observed around the 50-55% accuracy mark. This suggests potential areas for refinement in model training or data representation.

For future research, exploring a diverse range of machine learning models and augmenting the dataset could provide deeper insights and address the observed prediction imbalance. This study paves the way for further advancements in the application of machine learning in computational psychology, particularly in understanding and interpreting neuronal response patterns.
