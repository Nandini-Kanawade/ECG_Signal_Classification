# ECG Heartbeat Classification

## Overview
Electrocardiography (ECG) is a non-invasive test that measures the electrical activity of the heart. In this project, we focus on the classification of ECG heartbeat data into normal and abnormal categories using machine learning and deep learning algorithms. The report discusses the dataset, classification algorithms, results, and conclusions drawn from the analysis.

## Dataset
The dataset used in this study is the Physikalisch-Technische Bundesanstalt Database (PTBDB), containing 14,552 samples of ECG signals. It is divided into two classes: normal (4,046 samples) and abnormal (10,506 samples). After preprocessing, the dataset features are in the range [0,1], and there are no outliers.

## Algorithms
We explore several classification algorithms for binary classification of ECG heartbeat data:

- Naïve Bayes
- Logistic Regression
- Support Vector Machine
- Decision Tree
- Random Forest
- Perceptron Model
- Neural Networks (Dense, LSTM, Convolutional)

## Results
| Model               | Accuracy   |
|---------------------|------------|
| Naïve Bayes         | 62.67%     |
| Logistic Regression | 81.86%     |
| SVM (Linear Kernel) | 82.58%     |
| SVM (RBF Kernel)    | 91.03%     |
| Decision Tree       | 92.33%     |
| Random Forest       | 97.32%     |
| Perceptron Model    | 74.54%     |
| Neural Networks (Dense)   | 95.12% |
| Neural Networks (LSTM + Dense) | 96.49% |
| Neural Networks (Conv)   | 97.45% |

## Conclusion
The project demonstrates the effectiveness of various classification algorithms in accurately categorizing ECG heartbeat data. Random Forest and Convolutional Neural Network (CNN) achieved the highest accuracies, indicating their suitability for ECG classification tasks. The choice of model depends on factors such as dataset size, computational resources, interpretability requirements, and desired balance between accuracy and simplicity.

Further fine-tuning, feature engineering, and validation on external datasets could enhance the robustness and generalization capabilities of the models.

Feel free to explore the code and experiment with different algorithms!
