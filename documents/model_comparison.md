### megaDNA_145M

Original embeddings count: 8069 <br>
Matched embeddings count: 7997 <br>
Number of genus classes: 506 <br>
Number of family classes: 69 <br>
Number of class classes: 10 <br>
Number of host classes: 131 <br>
<br>
Train Loss: 0.6325, Val Loss: 0.8356 <br>
Train Accuracies: {'genus': '0.9348', 'family': '0.9942', 'class': '0.9990', 'host': '0.8615'} <br>
Val Accuracies: {'genus': '0.9450', 'family': '0.9975', 'class': '1.0000', 'host': '0.8675'} <br>
<br>
Test: <br>
Class prediction accuracy: 0.7936 <br>
Family prediction accuracy: 0.6506 <br>
Host prediction accuracy: 0.0916 <br>

### evo2_7b

**the run was stopped at around 89% of the progress** <br>
Original embeddings count: 21312 <br>
Matched embeddings count: 6555 <br>
Number of genus classes: 358 <br>
Number of family classes: 55 <br>
Number of class classes: 10 <br>
Number of host classes: 108 <br>
<br>
Train Loss: 1.4409, Val Loss: 1.4685 <br>
Train Accuracies: {'genus': '0.8501', 'family': '0.9712', 'class': '0.9849', 'host': '0.7696'} <br>
Val Accuracies: {'genus': '0.9162', 'family': '0.9802', 'class': '0.9954', 'host': '0.8079'} <br>

Test: <br>
Class prediction accuracy: 0.7647 <br>
Family prediction accuracy: 0.7531 <br>
Host prediction accuracy: 0.0308 <br>

--- Testing on CLASS task ---
Number of test samples: 8959
Class prediction accuracy: 0.7647
                  precision    recall  f1-score   support

  Caudoviricetes       1.00      0.76      0.87      8950
  Faserviricetes       0.01      1.00      0.02         4
Tectiliviricetes       0.14      1.00      0.25         5

       micro avg       0.94      0.76      0.84      8959
       macro avg       0.38      0.92      0.38      8959
    weighted avg       1.00      0.76      0.87      8959


--- Testing on FAMILY task ---
Number of test samples: 133
Warning: 52 samples have unknown labels and will be excluded
Family prediction accuracy: 0.7531
                   precision    recall  f1-score   support

Autographiviridae       0.91      0.85      0.88        59
   Drexlerviridae       0.67      1.00      0.80         2
   Herelleviridae       0.00      0.00      0.00         4
       Inoviridae       1.00      1.00      1.00         4
...
        micro avg       0.91      0.75      0.82        81
        macro avg       0.60      0.64      0.61        81
     weighted avg       0.79      0.75      0.77        81

--- Testing on HOST task ---
Number of test samples: 9040
Warning: 7028 samples have unknown labels and will be excluded
Host prediction accuracy: 0.0308
                  precision    recall  f1-score   support

   Acinetobacter       0.00      0.00      0.00         4
   Agrobacterium       0.00      0.00      0.00        43
        Bacillus       0.00      0.00      0.00         1
      Bordetella       0.00      0.00      0.00         1
     Citrobacter       0.00      0.00      0.00        10
     Cronobacter       0.00      0.00      0.00         6
    Enterobacter       0.00      0.00      0.00        24
    Enterococcus       0.00      0.00      0.00         8
         Erwinia       0.00      0.00      0.00       103
     Escherichia       0.03      0.27      0.05        22
 Exiguobacterium       0.00      0.00      0.00         2
  Flavobacterium       1.00      0.15      0.27        13
          Hafnia       0.00      0.00      0.00        49
      Klebsiella       0.01      0.25      0.02        24
       Kosakonia       0.00      0.00      0.00         1
       Leclercia       0.00      0.00      0.00         5
   Mesorhizobium       0.00      0.00      0.00         4
  Microbacterium       0.36      0.31      0.33        26
...
       micro avg       0.05      0.03      0.04      2012
       macro avg       0.05      0.05      0.03      2012
    weighted avg       0.04      0.03      0.03      2012


### evo2_40b
10474 sequences in the input; only got 3150 due to memory issue; batch size = 2
Original embeddings count: 3150
Matched embeddings count: 3150
Train Loss: 2.6096, Val Loss: 2.6637
Train Accuracies: {'genus': '0.8208', 'family': '0.8787', 'class': '0.8861', 'host': '0.6952'}
Val Accuracies: {'genus': '0.8190', 'family': '0.8857', 'class': '0.8794', 'host': '0.7333'}

Test
9345 seqs in the input; only got 5344
Class prediction accuracy: 0.1334
Family prediction accuracy: 0.0571
Host prediction accuracy: 0.0298
