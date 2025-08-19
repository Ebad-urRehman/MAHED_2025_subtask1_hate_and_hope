
```
📊 Hope Classifier Report:
              precision    recall  f1-score   support

    not_hope       0.87      0.81      0.84       967
        hope       0.68      0.76      0.72       509

    accuracy                           0.79      1476
   macro avg       0.77      0.79      0.78      1476
weighted avg       0.80      0.79      0.80      1476
```

![Hope Test set](hope_validation.png)

```
📊 Hate Classifier Report:
              precision    recall  f1-score   support

    not_hate       0.97      0.92      0.95      1318
        hate       0.55      0.77      0.64       158

    accuracy                           0.91      1476
   macro avg       0.76      0.85      0.79      1476
weighted avg       0.93      0.91      0.91      1476
```

![Hate Test set](hate_validation.png)

```
📊 Meta Classifier Report (Final Prediction):
                precision    recall  f1-score   support

          hope       0.69      0.74      0.71       509
          hate       0.56      0.76      0.65       158
not_applicable       0.77      0.69      0.73       809

      accuracy                           0.71      1476
     macro avg       0.67      0.73      0.70      1476
  weighted avg       0.72      0.71      0.71      1476
```
![Meta Test set](meta_validation.png)
