# Deep Learning Project : Facial Emotion Recognition with KAN

## Introduction
This project focuses on enhancing facial emotion recognition through a novel deep learning approach. We aim to leverage the Kolmogorov-Arnold Network (KAN) to improve the accuracy and interpretability of emotion classification.

## Dataset
The FER2013 dataset is utilized, comprising 35,887 grayscale images categorized into seven emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.

## Methodology
Our approach builds upon a Convolutional Neural Network (CNN) architecture, similar to the baseline established by GSNCodes. The key innovation lies in replacing traditional dense layers with a Kolmogorov-Arnold Network (KAN) to potentially enhance non-linear function approximation capabilities.

## Evaluation Metrics
Performance will be assessed using standard metrics:
- Accuracy
- Precision
- Recall
- F1-score

## Results

**Final Test Accuracy:** 69.21%
### baseline
https://github.com/GSNCodes/Emotion-Detection-FER2013/blob/master/Emotion_Recognition_Train.ipynb

### Detailed Classification Report:
```
              precision    recall  f1-score   support

       Angry       0.59      0.61      0.60       491
     Disgust       0.77      0.60      0.67        55
        Fear       0.56      0.56      0.56       528
       Happy       0.88      0.90      0.89       879
         Sad       0.61      0.51      0.56       594
    Surprise       0.84      0.77      0.80       416
     Neutral       0.61      0.70      0.65       626

    accuracy                           0.69      3589
   macro avg       0.69      0.67      0.68      3589
weighted avg       0.69      0.69      0.69      3589
```

## Conclusion
We anticipate the CNN + KAN integrated model to outperform the baseline CNN in accuracy and other metrics, offering improved recognition of facial emotions and potentially greater model interpretability.
