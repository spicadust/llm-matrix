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

--- Testing on CLASS task ---
Number of test samples: 9210
Class prediction accuracy: 0.7936
                  precision    recall  f1-score   support

  Caudoviricetes       1.00      0.79      0.88      9201
  Faserviricetes       0.01      1.00      0.01         4
Tectiliviricetes       0.01      1.00      0.03         5

       micro avg       0.88      0.79      0.83      9210
       macro avg       0.34      0.93      0.31      9210
    weighted avg       1.00      0.79      0.88      9210


--- Testing on FAMILY task ---
Number of test samples: 135
Warning: 52 samples have unknown labels and will be excluded
Family prediction accuracy: 0.6506
                   precision    recall  f1-score   support

Autographiviridae       0.90      0.72      0.80        61
   Drexlerviridae       0.67      1.00      0.80         2
   Herelleviridae       0.00      0.00      0.00         4
       Inoviridae       1.00      1.00      1.00         4
     Tectiviridae       0.75      0.60      0.67         5
    Zobellviridae       1.00      0.14      0.25         7

        micro avg       0.89      0.65      0.75        83
        macro avg       0.72      0.58      0.59        83
     weighted avg       0.85      0.65      0.72        83


--- Testing on HOST task ---
Number of test samples: 9305
Warning: 7066 samples have unknown labels and will be excluded
Host prediction accuracy: 0.0916
                  precision    recall  f1-score   support

   Achromobacter       0.00      0.00      0.00         7
   Acinetobacter       0.00      0.00      0.00         4
   Agrobacterium       0.00      0.00      0.00        44
        Bacillus       0.09      1.00      0.17         1
     Bacteroides       0.00      0.00      0.00        21
      Bordetella       0.00      0.00      0.00         1
     Citrobacter       0.00      0.00      0.00        10
     Clavibacter       0.00      0.00      0.00        13
 Corynebacterium       0.00      0.00      0.00         1
     Cronobacter       0.00      0.00      0.00         6
    Enterobacter       0.00      0.00      0.00        24
    Enterococcus       1.00      0.12      0.22         8
         Erwinia       0.22      0.05      0.08       106
     Escherichia       0.02      0.14      0.03        22
 Exiguobacterium       0.00      0.00      0.00         2
  Flavobacterium       1.00      0.62      0.76        13
        Gordonia       0.08      0.33      0.12         3
          Hafnia       0.00      0.00      0.00        50
      Klebsiella       0.03      0.32      0.06        25
       Kosakonia       0.00      0.00      0.00         1
   Lactobacillus       0.00      0.00      0.00         1
       Leclercia       0.00      0.00      0.00         5
   Mesorhizobium       0.00      0.00      0.00         4
  Microbacterium       0.29      0.18      0.22        28
      Morganella       0.00      0.00      0.00         2
   Mycobacterium       0.21      0.02      0.04       131
          Nostoc       0.00      0.00      0.00         5
         Pantoea       0.00      0.00      0.00       260
  Pectobacterium       0.00      0.00      0.00         2
         Proteus       0.00      0.00      0.00         3
     Providencia       0.00      0.00      0.00         8
     Pseudomonas       0.63      0.29      0.40       572
       Rhizobium       0.00      0.00      0.00        34
     Rhodococcus       0.00      0.00      0.00        45
      Salmonella       0.00      0.00      0.00        11
        Serratia       0.00      0.00      0.00        20
   Sinorhizobium       0.00      0.00      0.00         6
    Sphingomonas       0.00      0.00      0.00       664
Stenotrophomonas       0.01      0.18      0.03        11
    Streptomyces       0.00      0.00      0.00        41
          Vibrio       0.02      0.11      0.04         9
     Xanthomonas       0.25      0.50      0.33         2
        Yersinia       0.02      0.08      0.03        13

       micro avg       0.18      0.09      0.12      2239
       macro avg       0.09      0.09      0.06      2239
    weighted avg       0.20      0.09      0.12      2239

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

--- Testing on CLASS task ---
Number of test samples: 5344
Class prediction accuracy: 0.1334
                  precision    recall  f1-score   support

  Caudoviricetes       1.00      0.13      0.24      5335
  Faserviricetes       0.00      0.50      0.00         4
Tectiliviricetes       0.00      0.00      0.00         5

       micro avg       0.31      0.13      0.19      5344
       macro avg       0.33      0.21      0.08      5344
    weighted avg       1.00      0.13      0.23      5344


--- Testing on FAMILY task ---
Number of test samples: 80
Warning: 45 samples have unknown labels and will be excluded
Family prediction accuracy: 0.0571
                   precision    recall  f1-score   support

Autographiviridae       0.00      0.00      0.00        23
   Herelleviridae       0.00      0.00      0.00         3
       Inoviridae       0.22      0.50      0.31         4
     Tectiviridae       0.00      0.00      0.00         5
...
        micro avg       0.20      0.06      0.09        35
        macro avg       0.06      0.12      0.08        35
     weighted avg       0.03      0.06      0.04        35

--- Testing on HOST task ---
Number of test samples: 5404
Warning: 4968 samples have unknown labels and will be excluded
Host prediction accuracy: 0.0298
                  precision    recall  f1-score   support

   Acinetobacter       0.00      0.00      0.00         2
    Enterococcus       0.00      0.00      0.00         1
         Erwinia       0.00      0.00      0.00        50
     Escherichia       0.05      0.40      0.09        10
  Flavobacterium       0.00      0.00      0.00         8
      Klebsiella       0.00      0.00      0.00         9
  Microbacterium       0.27      0.35      0.31        17
     Pseudomonas       0.29      0.01      0.01       278
     Rhodococcus       0.00      0.00      0.00        26
      Salmonella       0.00      0.00      0.00         3
Stenotrophomonas       0.00      0.00      0.00         5
    Streptomyces       0.00      0.00      0.00        21
          Vibrio       0.00      0.00      0.00         4
     Xanthomonas       0.03      0.50      0.05         2

       micro avg       0.06      0.03      0.04       436
       macro avg       0.05      0.09      0.03       436
    weighted avg       0.19      0.03      0.02       436


### megaDNA 277M

Original embeddings count: 8069
Matched embeddings count: 7997
Percentage retained: 99.11%
Number of genus classes: 506
Number of family classes: 69
Number of class classes: 10
Number of host classes: 131
Epoch 20/20
Train Loss: 0.5488, Val Loss: 0.8423
Train Accuracies: {'genus': '0.9464', 'family': '0.9954', 'class': '0.9992', 'host': '0.8816'}
Val Accuracies: {'genus': '0.9525', 'family': '0.9962', 'class': '1.0000', 'host': '0.8800'}