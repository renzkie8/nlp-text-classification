# Original recorded metric excerpts

These are selected metric outputs from the supplied notebooks, not a new execution. Interpret them with the source methodology and submitted report.

## PS3_Colico.ipynb

```text
Training MultinomialNB
--- MultinomialNB ---
Accuracy: 0.7975
              precision    recall  f1-score   support

           0     0.8018    0.9398    0.8653       581
           1     0.7374    0.9899    0.8452       695
           2     1.0000    0.2453    0.3939       159
           3     0.9497    0.6182    0.7489       275
           4     0.9006    0.6473    0.7532       224
           5     1.0000    0.1061    0.1918        66

    accuracy                         0.7975      2000
   macro avg     0.8983    0.5911    0.6331      2000
weighted avg     0.8331    0.7975    0.7701      2000

```

## PS3_Colico.ipynb

```text
Training LogisticRegression
--- LogisticRegression ---
Accuracy: 0.894
              precision    recall  f1-score   support

           0     0.9214    0.9484    0.9347       581
           1     0.8708    0.9698    0.9176       695
           2     0.8480    0.6667    0.7465       159
           3     0.9031    0.8473    0.8743       275
           4     0.9048    0.8482    0.8756       224
           5     0.9714    0.5152    0.6733        66

    accuracy                         0.8940      2000
   macro avg     0.9032    0.7992    0.8370      2000
weighted avg     0.8953    0.8940    0.8902      2000

```

## PS3_Colico.ipynb

```text
Training LinearSupportVectorMachine
--- LinearSupportVectorMachine ---
Accuracy: 0.904
              precision    recall  f1-score   support

           0     0.9481    0.9432    0.9456       581
           1     0.9176    0.9295    0.9235       695
           2     0.7826    0.7925    0.7875       159
           3     0.8993    0.9091    0.9042       275
           4     0.8853    0.8616    0.8733       224
           5     0.7377    0.6818    0.7087        66

    accuracy                         0.9040      2000
   macro avg     0.8618    0.8529    0.8571      2000
weighted avg     0.9037    0.9040    0.9038      2000

```

## PS3_Colico.ipynb

```text
============================================================
1. ACCURACY COMPARISON
============================================================
                     Model  Accuracy
LinearSupportVectorMachine    0.9040
        LogisticRegression    0.8940
             MultinomialNB    0.7975

✓ Best Accuracy: LinearSupportVectorMachine (0.9040)

============================================================
2. PRECISION, RECALL & F1-SCORE SUMMARY
============================================================

MultinomialNB:
              precision    recall  f1-score   support

           0     0.8018    0.9398    0.8653       581
           1     0.7374    0.9899    0.8452       695
           2     1.0000    0.2453    0.3939       159
           3     0.9497    0.6182    0.7489       275
           4     0.9006    0.6473    0.7532       224
           5     1.0000    0.1061    0.1918        66

    accuracy                         0.7975      2000
   macro avg     0.8983    0.5911    0.6331      2000
weighted avg     0.8331    0.7975    0.7701      2000


LogisticRegression:
              precision    recall  f1-score   support

           0     0.9214    0.9484    0.9347       581
           1     0.8708    0.9698    0.9176       695
           2     0.8480    0.6667    0.7465       159
           3     0.9031    0.8473    0.8743       275
           4     0.9048    0.8482    0.8756       224
           5     0.9714    0.5152    0.6733        66

    accuracy                         0.8940      2000
   macro avg     0.9032    0.7992    0.8370      2000
weighted avg     0.8953    0.8940    0.8902      2000


LinearSupportVectorMachine:
              precision    recall  f1-score   support

           0     0.9481    0.9432    0.9456       581
           1     0.9176    0.9295    0.9235       695
           2     0.7826    0.7925    0.7875       159
           3     0.8993    0.9091    0.9042       275
           4     0.8853    0.8616    0.8733       224
           5     0.7377    0.6818    0.7087        66

    accuracy                         0.9040      2000
   macro avg     0.8618    0.8529    0.8571      2000
weighted avg     0.9037    0.9040    0.9038      2000


============================================================
3. CONFUSION MATRIX ANALYSIS
============================================================

MultinomialNB:
  Correct predictions: 1595/2000
  Per-class accuracy: ['546/(581 total)', '688/(695 total)', '39/(159 total)', '170/(275 total)', '145/(224 total)', '7/(66 total)']

LogisticRegression:
  Correct predictions: 1788/2000
  Per-class accuracy: ['551/(581 total)', '674/(695 total)', '106/(159 total)', '233/(275 total)', '190/(224 total)', '34/(66 total)']

LinearSupportVectorMachine:
  Correct predictions: 1808/2000
  Per-class accuracy: ['548/(581 total)', '646/(695 total)', '126/(159 total)', '250/(275 total)', '193/(224 total)', '45/(66 total)']

============================================================
4. OVERALL RECOMMENDATION
============================================================

✓ Best Overall Model: LinearSupportVectorMachine
  - Highest accuracy: 0.9040
  - Second best: LogisticRegression (0.8940)
  - Third: MultinomialNB (0.7975)

Key Findings:
  • Review classification reports for precision/recall trade-offs
  • Confusion matrices show which classes are most often confused
  • Consider domain requirements when choosing between models
  • High F1-score indicates good balance between precision and recall
```

