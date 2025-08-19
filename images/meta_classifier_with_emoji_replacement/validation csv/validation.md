
```
📊 Hope Classifier Report:
              precision    recall  f1-score   support

    not_hope       0.87      0.91      0.89       967
        hope       0.81      0.73      0.77       509

    accuracy                           0.85      1476
   macro avg       0.84      0.82      0.83      1476
weighted avg       0.85      0.85      0.85      1476
```

![Hope Test set](hope_validation.png)

```
📊 Hate Classifier Report:
              precision    recall  f1-score   support

    not_hate       0.99      0.85      0.91      1318
        hate       0.43      0.93      0.58       158

    accuracy                           0.86      1476
   macro avg       0.71      0.89      0.75      1476
weighted avg       0.93      0.86      0.88      1476
```

![Hate Test set](hate_validation.png)

```
📊 Meta Classifier Report (Final Prediction):
                precision    recall  f1-score   support

          hope       0.82      0.71      0.76       509
          hate       0.46      0.91      0.61       158
not_applicable       0.80      0.71      0.76       809

      accuracy                           0.73      1476
     macro avg       0.69      0.78      0.71      1476
  weighted avg       0.77      0.73      0.74      1476
```
![Meta Test set](meta_validation.png)
