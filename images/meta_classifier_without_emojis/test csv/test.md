
```
📊 Hope Classifier Report:
              precision    recall  f1-score   support

    not_hope       0.97      0.95      0.96      1055
        hope       0.88      0.94      0.91       422

    accuracy                           0.94      1477
   macro avg       0.93      0.94      0.93      1477
weighted avg       0.95      0.94      0.95      1477
```

![Hope Test set](hope_test.png)

```
📊 Hate Classifier Report:
              precision    recall  f1-score   support

    not_hate       0.98      0.99      0.98      1190
        hate       0.94      0.90      0.92       287

    accuracy                           0.97      1477
   macro avg       0.96      0.94      0.95      1477
weighted avg       0.97      0.97      0.97      1477
```

![Hate Test set](hate_test.png)

```

📊 Meta Classifier Report (Final Prediction):
                precision    recall  f1-score   support

          hope       0.88      0.93      0.91       422
          hate       0.94      0.90      0.92       287
not_applicable       0.92      0.91      0.92       768

      accuracy                           0.91      1477
     macro avg       0.92      0.91      0.91      1477
  weighted avg       0.91      0.91      0.91      1477
```
![Meta Test set](meta_test.png)
