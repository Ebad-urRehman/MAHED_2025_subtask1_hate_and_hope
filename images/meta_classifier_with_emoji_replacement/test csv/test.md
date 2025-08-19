
```
📊 Hope Classifier Report:
              precision    recall  f1-score   support

    not_hope       0.86      0.81      0.83      1055
        hope       0.58      0.68      0.63       422

    accuracy                           0.77      1477
   macro avg       0.72      0.74      0.73      1477
weighted avg       0.78      0.77      0.77      1477
```

![Hope Test set](hope_test.png)

```
📊 Hate Classifier Report:
              precision    recall  f1-score   support

    not_hate       0.92      0.87      0.90      1190
        hate       0.56      0.70      0.63       287

    accuracy                           0.84      1477
   macro avg       0.74      0.79      0.76      1477
weighted avg       0.85      0.84      0.84      1477
```

![Hate Test set](hate_test.png)

```
📊 Meta Classifier Report (Final Prediction):
                precision    recall  f1-score   support

          hope       0.58      0.67      0.62       422
          hate       0.58      0.67      0.62       287
not_applicable       0.69      0.60      0.64       768

      accuracy                           0.63      1477
     macro avg       0.62      0.64      0.63      1477
  weighted avg       0.64      0.63      0.63      1477
```
![Meta Test set](meta_test.png)
