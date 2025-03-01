## Recognizing Ethnic Groups from Speech Using Machine Learning

### Abstract
This project focuses on creating a system to recognize the ethnic group of British speakers in Birmingham as either 'Asian' or 'White' based on their speech. Using common speech processing features such as Energy, Zero-Crossing Rate, Pitch Frequency, and Mel-Frequency Cepstral Coefficients (MFCCs) with deltas and delta-delta, we experimented with various machine learning models to achieve the best accuracy.

### Introduction
Speech recognition and classification play an important role in modern technology, from voice assistants to understanding linguistic diversity. This project focuses on identifying the ethnic group of British speakers in Birmingham by extracting key features like Energy, Zero-Crossing Rate, Pitch Frequency, and MFCCs. We apply machine learning models such as k-Nearest Neighbors (KNN) and Gaussian Mixture Models (GMM) to classify the speakers. 

### Methodology
The project involves processing audio data, extracting relevant features, and fine-tuning the models to achieve reliable results. We experimented with different models and parameters to find the best performance, ultimately achieving a 77.5% accuracy with the Gaussian Mixture Model (GMM) and a 62.5% accuracy with the k-Nearest Neighbors (KNN) model.

### Conclusion
This project demonstrates the potential of combining basic speech features and machine learning techniques for ethnic group recognition. Despite some limitations, the results showcase promising accuracy levels. Future work aims to improve accuracy through larger datasets and more advanced methods.

### Future Work
Future improvements include expanding the dataset, incorporating advanced features, and using deep learning models such as Convolutional Neural Networks (CNNs) or Recurrent Neural Networks (RNNs). Better tuning of the models and combining different methods could further enhance the system's performance.

### References
1. Analytics Vidhya, "MFCC Technique for Speech Recognition," [Online].
2. Spoken Language Processing Course Slides, 2024–2025.
3. IBM, "K-Nearest Neighbors Algorithm," [Online].
4. CmdLineTips, "Gaussian Mixture Models with Scikit-learn in Python," [Online].
5. Applied AI Course, "Gaussian Mixture Model in Machine Learning," [Online].
6. Scikit-learn, "Grid Search," [Online].
7. Wikipedia, "Energy (Signal Processing)," [Online].
