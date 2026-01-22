Fake Currency Detection

This project focuses on detecting counterfeit banknotes using statistical features extracted from images. Machine learning models are trained to classify banknotes as real or fake, enabling accurate and efficient currency authentication.

Dataset

The UCI Banknote Authentication Dataset is used, containing features extracted from genuine and forged banknote images: variance, skewness, kurtosis, and entropy.

Feature Engineering

Variance – texture variation of the banknote
Skewness – asymmetry of pixel distribution
Kurtosis – sharpness / peaks
Entropy – randomness of pixel intensity

Anomaly Detection / Classification Techniques

Logistic Regression
Random Forest Classifier

Results

Logistic Regression achieved [Your LR Accuracy]% accuracy.
Random Forest achieved [Your RF Accuracy]% accuracy.
Models successfully classify new banknotes and provide predictions for authenticity.

Technologies Used

Python
Pandas, Numpy
Scikit-learn
Matplotlib, Seaborn

Future Work

Extend to image-based deep learning models (CNNs) for direct image classification
Deploy as a web app or mobile application for real-time currency authentication
Experiment with other ML algorithms for higher accuracy
