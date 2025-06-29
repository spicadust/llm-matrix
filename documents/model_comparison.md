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

--- Testing on **CLASS** task ---
Number of test samples: 9210
Class prediction accuracy: 0.7936
                  precision    recall  f1-score   support

  Caudoviricetes       1.00      0.79      0.88      9201
  Faserviricetes       0.01      1.00      0.01         4
Tectiliviricetes       0.01      1.00      0.03         5

       micro avg       0.88      0.79      0.83      9210
       macro avg       0.34      0.93      0.31      9210
    weighted avg       1.00      0.79      0.88      9210


--- Testing on **FAMILY** task ---
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


--- Testing on **HOST** task ---
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

--- Testing on **CLASS** task ---
Number of test samples: 8959
Class prediction accuracy: 0.7647
                  precision    recall  f1-score   support

  Caudoviricetes       1.00      0.76      0.87      8950
  Faserviricetes       0.01      1.00      0.02         4
Tectiliviricetes       0.14      1.00      0.25         5

       micro avg       0.94      0.76      0.84      8959
       macro avg       0.38      0.92      0.38      8959
    weighted avg       1.00      0.76      0.87      8959


--- Testing on **FAMILY** task ---
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

--- Testing on **HOST** task ---
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


### megaDNA277M

- manual hierarchical loss
  
Train Loss: 0.4012, Val Loss: 0.4983
Train Accuracies: {'Genus': '0.7801', 'Sub-family': '0.9440', 'Family': '0.9556', 'Order': '0.9969', 'Class': '0.9622', 'Phylum': '0.9620', 'Kingdom': '0.9621', 'Realm': '0.9621', 'Host_phylum': '0.9879', 'Host_class': '0.9825', 'Host_order': '0.9545', 'Host_family': '0.9263', 'Host_genus': '0.8698'}
Val Accuracies: {'Genus': '0.8211', 'Sub-family': '0.9599', 'Family': '0.9692', 'Order': '0.9990', 'Class': '0.9617', 'Phylum': '0.9620', 'Kingdom': '0.9617', 'Realm': '0.9617', 'Host_phylum': '0.9892', 'Host_class': '0.9829', 'Host_order': '0.9475', 'Host_family': '0.9260', 'Host_genus': '0.8750'}
Early stopping triggered

#### train_millard; test_matrix
Number of test samples: 8360

Viral **Genus** Accuracy: 0.5294
Number of test samples: 17
Number of classes in test: 14

Classification Report:
                 precision    recall  f1-score   support

    Berlinvirus       1.00      1.00      1.00         1
    Cronosvirus       0.00      0.00      0.00         1
     Dibbivirus       1.00      1.00      1.00         1
      Eganvirus       0.50      1.00      0.67         1
     Elunavirus       0.00      0.00      0.00         1
 Eracentumvirus       0.00      0.00      0.00         1
 Irrigatiovirus       0.00      0.00      0.00         1
   Kayfunavirus       1.00      1.00      1.00         1
  Loessnervirus       1.00      1.00      1.00         1
    Murrayvirus       0.00      0.00      0.00         1
    Pahexavirus       1.00      0.50      0.67         2
Sauletekiovirus       0.00      0.00      0.00         1
   Sendosyvirus       1.00      0.50      0.67         2
    Uliginvirus       1.00      1.00      1.00         2

      micro avg       0.90      0.53      0.67        17
      macro avg       0.54      0.50      0.50        17
   weighted avg       0.62      0.53      0.55        17


Viral **Sub-family** Accuracy: 0.8750
Number of test samples: 8
Number of classes in test: 5

Classification Report:
                  precision    recall  f1-score   support

Cleopatravirinae       1.00      1.00      1.00         1
  Colwellvirinae       1.00      1.00      1.00         2
   Melnykvirinae       0.00      0.00      0.00         1
 Molineuxvirinae       1.00      1.00      1.00         1
  Studiervirinae       1.00      1.00      1.00         3

       micro avg       1.00      0.88      0.93         8
       macro avg       0.80      0.80      0.80         8
    weighted avg       0.88      0.88      0.88         8


Viral **Family** Accuracy: 0.0460
Number of test samples: 4888
Number of classes in test: 18
**Obervation: the model can predict better for some families; precision >> recall, which means that the prediction the model made is out of the testing labels.**
**possible problem: too few samples in the training set for some labels**


Classification Report:
                     precision    recall  f1-score   support

   Ackermannviridae       0.00      0.00      0.00        17
  Autographiviridae       0.41      0.34      0.37       168
     Casjensviridae       0.71      0.02      0.03       303
       Chaseviridae       0.17      0.01      0.01       131
     Demerecviridae       0.00      0.00      0.00         9
     Drexlerviridae       0.00      0.00      0.00       390
     Herelleviridae       0.00      0.00      0.00        30
       Kyanoviridae       0.00      0.00      0.00        76
Mesyanzhinovviridae       0.29      0.00      0.01       520
  Orlajensenviridae       0.00      0.00      0.00       613
       Peduoviridae       0.82      0.10      0.17      1487
    Rountreeviridae       0.00      0.00      0.00         1
     Salasmaviridae       0.00      0.00      0.00        66
      Schitoviridae       1.00      0.18      0.30        67
      Straboviridae       0.00      0.00      0.00        21
       Vilmaviridae       0.00      0.00      0.00       617
      Zierdtviridae       1.00      0.00      0.01       336
      Zobellviridae       0.50      0.06      0.10        36

          micro avg       0.63      0.05      0.09      4888
          macro avg       0.27      0.04      0.06      4888
       weighted avg       0.43      0.05      0.07      4888


No valid test samples for viral **Order**

Viral **Class** Accuracy: 0.9626
Number of test samples: 4894
Number of classes in test: 1

Classification Report:
                precision    recall  f1-score   support

Caudoviricetes       1.00      0.96      0.98      4894

     micro avg       1.00      0.96      0.98      4894
     macro avg       1.00      0.96      0.98      4894
  weighted avg       1.00      0.96      0.98      4894


Viral **Phylum** Accuracy: 0.9616
Number of test samples: 4894
Number of classes in test: 1

Classification Report:
              precision    recall  f1-score   support

 Uroviricota       1.00      0.96      0.98      4894

   micro avg       1.00      0.96      0.98      4894
   macro avg       1.00      0.96      0.98      4894
weighted avg       1.00      0.96      0.98      4894


Viral **Kingdom** Accuracy: 1.0000
Number of test samples: 17
Number of classes in test: 1

Classification Report:
                precision    recall  f1-score   support

Heunggongvirae       1.00      1.00      1.00        17

      accuracy                           1.00        17
     macro avg       1.00      1.00      1.00        17
  weighted avg       1.00      1.00      1.00        17


Warning: Found 3 unknown host Host_phylum labels in test data:
Unknown labels: {'Chloroflexota', 'Candidatus Saccharibacteria', 'Nitrospirota'}
These samples will be excluded from evaluation

Host **Host_phylum** Accuracy: 0.7534
Number of test samples: 3272
Number of classes in test: 7

Classification Report:
                 precision    recall  f1-score   support

 Actinomycetota       0.75      0.85      0.79       543
      Bacillota       0.70      0.70      0.70        27
   Bacteroidota       0.86      0.02      0.04       334
Cyanobacteriota       0.00      0.14      0.01         7
   Deinococcota       0.00      0.00      0.00        11
 Fusobacteriota       0.00      0.00      0.00         1
 Pseudomonadota       0.85      0.84      0.85      2349

      micro avg       0.76      0.75      0.75      3272
      macro avg       0.45      0.36      0.34      3272
   weighted avg       0.83      0.75      0.75      3272


Warning: Found 6 unknown host Host_class labels in test data:
Unknown labels: {'Cytophagia', 'Sphingobacteriia', 'Anaerolineae', 'Candidatus Saccharimonadia', 'Negativicutes', 'Nitrospiria'}
These samples will be excluded from evaluation

Host **Host_class** Accuracy: 0.6523
Number of test samples: 2965
Number of classes in test: 12

Classification Report:
                     precision    recall  f1-score   support

      Actinomycetes       0.75      0.83      0.79       536
Alphaproteobacteria       0.90      0.24      0.38       984
            Bacilli       0.70      0.93      0.80        15
        Bacteroidia       1.00      0.04      0.08        24
 Betaproteobacteria       0.14      0.74      0.23        78
         Clostridia       1.00      0.30      0.46        10
     Coriobacteriia       1.00      0.29      0.44         7
       Cyanophyceae       0.00      0.14      0.01         7
         Deinococci       0.00      0.00      0.00        11
     Flavobacteriia       0.40      0.40      0.40         5
      Fusobacteriia       0.00      0.00      0.00         1
Gammaproteobacteria       0.85      0.91      0.88      1287

          micro avg       0.66      0.65      0.65      2965
          macro avg       0.56      0.40      0.37      2965
       weighted avg       0.82      0.65      0.66      2965


Warning: Found 12 unknown host Host_order labels in test data:
Unknown labels: {'Geodermatophilales', 'Candidatus Saccharimonadales', 'Cytophagales', 'Sphingobacteriales', 'Legionellales', 'Aggregatilineales', 'Cellvibrionales', 'Deinococcales', 'Nitrospirales', 'Coriobacteriales', 'Methylococcales', 'Selenomonadales'}
These samples will be excluded from evaluation

Host **Host_order** Accuracy: 0.4528
Number of test samples: 2935
Number of classes in test: 28

Classification Report:
                     precision    recall  f1-score   support

    Actinomycetales       0.00      0.00      0.00         2
         Bacillales       0.23      0.75      0.35         4
      Bacteroidales       1.00      0.08      0.15        24
  Bifidobacteriales       0.23      0.50      0.32         6
    Burkholderiales       0.11      0.72      0.19        78
    Caulobacterales       0.00      0.00      0.00         3
   Enterobacterales       0.99      0.84      0.91       688
      Eubacteriales       0.20      0.12      0.15         8
   Flavobacteriales       0.50      0.60      0.55         5
    Fusobacteriales       0.00      0.00      0.00         1
   Hyphomicrobiales       0.41      0.12      0.19       300
   Kitasatosporales       0.36      0.16      0.22        25
     Lachnospirales       0.00      0.00      0.00         2
    Lactobacillales       0.43      0.27      0.33        11
     Lysobacterales       0.01      0.15      0.02        13
      Micrococcales       0.48      0.40      0.44       273
       Moraxellales       0.00      0.00      0.00         4
    Mycobacteriales       0.30      0.49      0.37       177
         Nostocales       0.00      0.00      0.00         5
  Oceanospirillales       0.00      0.00      0.00         2
    Oscillatoriales       0.00      0.00      0.00         1
Propionibacteriales       0.23      0.12      0.16        41
    Pseudomonadales       0.78      0.74      0.76       574
  Pseudonocardiales       0.00      0.00      0.00         3
    Rhodobacterales       0.00      0.00      0.00         1
   Sphingomonadales       0.77      0.01      0.03       680
    Synechococcales       0.00      0.00      0.00         1
        Vibrionales       0.00      0.00      0.00         3

          micro avg       0.47      0.45      0.46      2935
          macro avg       0.25      0.22      0.18      2935
       weighted avg       0.69      0.45      0.46      2935


Warning: Found 23 unknown host Host_family labels in test data:
Unknown labels: {'Atopobiaceae', 'Cellulomonadaceae', 'Nitrospiraceae', 'Sphingobacteriaceae', 'Hyphomicrobiaceae', 'Devosiaceae', 'Sphingosinicellaceae', 'Demequinaceae', 'Methylococcaceae', 'Selenomonadaceae', 'Hymenobacteraceae', 'Geodermatophilaceae', 'Coriobacteriaceae', 'Sanguibacteraceae', 'Cytophagaceae', 'Porticoccaceae', 'Coxiellaceae', 'Candidatus Saccharimonadaceae', 'Methylobacteriaceae', 'Deinococcaceae', 'Prevotellaceae', 'Candidatus Flexifilaceae', 'Nocardioidaceae'}
These samples will be excluded from evaluation

Host **Host_family** Accuracy: 0.2753
Number of test samples: 2750
Number of classes in test: 51

Classification Report:
                       precision    recall  f1-score   support

     Actinomycetaceae       0.00      0.00      0.00         2
       Alcaligenaceae       0.00      0.00      0.00         8
    Aurantimonadaceae       0.00      0.00      0.00        29
          Bacillaceae       0.00      0.00      0.00         2
       Bacteroidaceae       1.00      0.05      0.09        21
   Bifidobacteriaceae       0.27      0.50      0.35         6
         Brucellaceae       0.00      0.00      0.00         3
  Bruguierivoracaceae       0.00      0.00      0.00        17
     Burkholderiaceae       0.00      0.33      0.01         3
    Carnobacteriaceae       0.00      0.00      0.00         3
     Caulobacteraceae       0.00      0.00      0.00         3
       Comamonadaceae       0.17      0.03      0.04        40
   Corynebacteriaceae       0.00      0.00      0.00         1
   Enterobacteriaceae       0.19      0.79      0.31       127
      Enterococcaceae       1.00      0.25      0.40         8
          Erwiniaceae       0.69      0.02      0.05       368
   Erythrobacteraceae       0.00      0.00      0.00         2
    Flavobacteriaceae       0.33      0.50      0.40         2
     Fusobacteriaceae       0.00      0.00      0.00         1
         Gordoniaceae       0.00      0.00      0.00         3
           Hafniaceae       0.25      0.05      0.08        42
       Halomonadaceae       0.00      0.00      0.00         2
      Lachnospiraceae       0.00      0.00      0.00         2
      Lysobacteraceae       0.01      0.15      0.02        13
    Microbacteriaceae       0.52      0.45      0.48       246
       Micrococcaceae       0.05      0.13      0.07        15
       Microcoleaceae       0.00      0.00      0.00         1
        Moraxellaceae       0.00      0.00      0.00         4
       Morganellaceae       0.00      0.00      0.00        28
     Mycobacteriaceae       0.15      0.25      0.19       122
     Nitrobacteraceae       0.00      0.00      0.00         7
         Nocardiaceae       0.30      0.06      0.10        51
          Nostocaceae       0.00      0.00      0.00         5
     Oscillospiraceae       0.25      0.12      0.17         8
     Oxalobacteraceae       0.00      0.00      0.00        23
    Pectobacteriaceae       0.00      0.00      0.00         3
   Phyllobacteriaceae       0.00      0.00      0.00         7
   Prochlorococcaceae       0.00      0.00      0.00         1
Promicromonosporaceae       0.00      0.00      0.00         7
 Propionibacteriaceae       0.18      0.80      0.30         5
     Pseudomonadaceae       0.78      0.77      0.78       574
   Pseudonocardiaceae       0.00      0.00      0.00         3
         Rhizobiaceae       0.42      0.24      0.30       118
        Rikenellaceae       0.00      0.00      0.00         1
     Roseobacteraceae       0.00      0.00      0.00         1
      Sphaerotilaceae       0.00      0.00      0.00         1
    Sphingomonadaceae       0.43      0.00      0.01       677
    Streptomycetaceae       0.50      0.16      0.24        25
         Vibrionaceae       0.02      0.33      0.04         3
        Weeksellaceae       1.00      0.33      0.50         3
         Yersiniaceae       0.33      0.03      0.05       103

            micro avg       0.31      0.28      0.29      2750
            macro avg       0.17      0.12      0.10      2750
         weighted avg       0.48      0.28      0.26      2750


Warning: Found 97 unknown host Host_genus labels in test data:
Unknown labels: {'Hymenobacter', 'Collinsella', 'Maritimibacter', 'Afipia', 'Ruminiclostridium', 'Buttiauxella', 'Candidatus Flexicrinis', 'Pauljensenia', 'Sphingomicrobium', 'Kocuria', 'Photorhabdus', 'Demequina', 'Megamonas', 'Pedomonas', 'Rouxiella', 'Xenophilus', 'Williamsia', 'Microvirga', 'Nitrospira', 'Promicromonospora', 'Xenorhabdus', 'Paraburkholderia', 'Agromyces', 'Leifsonia', 'Pluralibacter', 'Chryseobacterium', 'Samsonia', 'Agreia', 'Pararhizobium', 'Candidatus Microsaccharimonas', 'Frigoribacterium', 'Pseudonocardia', 'Geodermatophilus', 'Thermophilibacter', 'Nocardioides', 'Deinococcus', 'Novosphingobium', 'Leucobacter', 'Klenkia', 'Tamlana', 'Phaseolibacter', 'Tenebrionibacter', 'Neorhizobium', 'Sanguibacter', 'Methylobacterium', 'Cryobacterium', 'Fictibacillus', 'Collimonas', 'Scandinavium', 'Parasynechococcus', 'Prevotella', 'Arachnia', 'Izhakiella', 'Smaragdicoccus', 'Candidatus Scatomonas', 'Shinella', 'Actinosynnema', 'Phyllobacterium', 'Candidatus Stercorousia', 'Aquibium', 'Marmoricola', 'Oerskovia', 'Comamonas', 'Cupriavidus', 'Plantibacter', 'Alloprevotella', 'Pedobacter', 'Polynucleobacter', 'Ensifer', 'Telluria', 'Spirosoma', 'Pseudorhizobium', 'Subtercola', 'Mixta', 'Duganella', 'Herbiconiux', 'Atlantibacter', 'Aureimonas', 'Rosenbergiella', 'Mediterraneibacter', 'Rickettsiella', 'Kibdelosporangium', 'Blastococcus', 'Methyloglobulus', 'Arsenophonus', 'Paenarthrobacter', 'Candidatus Regiella', 'Devosia', 'Ewingella', 'Methylibium', 'Mycoplana', 'Pelagerythrobacter', 'Hyphomicrobium', 'Porticoccus', 'Pseudescherichia', 'Frondihabitans', 'Epilithonimonas'}
These samples will be excluded from evaluation

Host **Host_genus** Accuracy: 0.2249
Number of test samples: 2481
Number of classes in test: 75

Classification Report:
                         precision    recall  f1-score   support

          Achromobacter       0.00      0.00      0.00         7
             Acidovorax       0.00      0.00      0.00         2
          Acinetobacter       0.00      0.00      0.00         4
          Agrobacterium       0.00      0.00      0.00        39
              Alistipes       0.00      0.00      0.00         1
            Aminobacter       0.00      0.00      0.00         2
           Arthrobacter       0.06      0.22      0.10         9
           Aurantimonas       0.00      0.00      0.00         1
               Bacillus       0.00      0.00      0.00         1
            Bacteroides       1.00      0.05      0.10        20
        Bifidobacterium       0.33      0.50      0.40         6
             Bordetella       0.00      0.00      0.00         1
         Bradyrhizobium       0.00      0.00      0.00         6
          Brevundimonas       0.00      0.00      0.00         3
Candidatus Hamiltonella       0.00      0.00      0.00         4
         Carnobacterium       0.00      0.00      0.00         3
     Cellulosimicrobium       0.00      0.00      0.00         5
            Citrobacter       0.00      0.00      0.00        11
            Clavibacter       0.00      0.00      0.00        13
        Corynebacterium       0.00      0.00      0.00         1
            Cronobacter       0.00      0.00      0.00         6
         Curtobacterium       0.17      0.01      0.02        96
          Cutibacterium       0.60      0.75      0.67         4
           Enterobacter       0.00      0.00      0.00        27
           Enterococcus       1.00      0.25      0.40         8
                Erwinia       0.25      0.03      0.06        97
          Erythrobacter       0.00      0.00      0.00         1
            Escherichia       0.10      0.34      0.15        29
        Exiguobacterium       0.00      0.00      0.00         2
       Faecalibacterium       0.33      1.00      0.50         1
         Flavobacterium       0.00      0.00      0.00         1
               Gordonia       0.00      0.00      0.00         3
                 Hafnia       0.00      0.00      0.00        42
              Halomonas       0.00      0.00      0.00         2
      Janthinobacterium       0.00      0.00      0.00         3
             Klebsiella       0.03      0.27      0.06        26
              Kosakonia       0.00      0.00      0.00         2
              Leclercia       0.00      0.00      0.00         5
          Mesorhizobium       0.00      0.00      0.00         3
         Microbacterium       0.06      0.43      0.11        23
            Microcoleus       0.00      0.00      0.00         1
             Morganella       0.00      0.00      0.00         1
          Mycobacterium       0.20      0.26      0.23       122
               Nocardia       0.00      0.00      0.00         2
                 Nostoc       0.00      0.00      0.00         5
           Ochrobactrum       0.00      0.00      0.00         3
                Pantoea       0.67      0.01      0.02       252
         Pectobacterium       0.00      0.00      0.00         2
            Phocaeicola       0.00      0.00      0.00         1
         Photobacterium       0.00      0.00      0.00         1
             Pontimonas       0.00      0.00      0.00         1
                Proteus       0.00      0.00      0.00         4
            Providencia       0.00      0.00      0.00        10
            Pseudomonas       0.78      0.81      0.79       561
      Pseudoxanthomonas       0.00      0.00      0.00         1
               Rahnella       0.00      0.00      0.00        44
          Rathayibacter       0.00      0.00      0.00        44
              Rhizobium       0.27      0.26      0.26        43
            Rhodococcus       0.14      0.05      0.07        42
           Ruminococcus       0.00      0.00      0.00         1
             Salmonella       0.03      0.38      0.06         8
               Serratia       0.50      0.12      0.19        17
          Sinorhizobium       0.00      0.00      0.00         5
                Sodalis       0.00      0.00      0.00        17
            Sphingobium       0.00      0.00      0.00        10
           Sphingomonas       0.00      0.00      0.00       655
           Sphingopyxis       0.00      0.00      0.00         1
       Stenotrophomonas       0.02      0.09      0.03        11
           Streptomyces       0.50      0.16      0.24        25
          Stutzerimonas       0.00      0.00      0.00        13
             Variovorax       0.00      0.00      0.00        28
                 Vibrio       0.03      0.50      0.05         2
            Xanthomonas       0.02      1.00      0.04         1
             Xylophilus       0.00      0.00      0.00         3
               Yersinia       0.06      0.08      0.07        24

              micro avg       0.32      0.22      0.26      2481
              macro avg       0.10      0.10      0.06      2481
           weighted avg       0.30      0.22      0.21      2481


#### train_millard; test_strain

Number of test samples: 3238

**Viral Family** Accuracy: 0.1740
Number of test samples: 2195
Number of classes in test: 15

Classification Report:
                     precision    recall  f1-score   support

   Ackermannviridae       0.00      0.00      0.00         6
  Autographiviridae       0.00      0.00      0.00         9
     Casjensviridae       0.00      0.00      0.00        26
       Chaseviridae       0.00      0.00      0.00        26
     Drexlerviridae       0.00      0.00      0.00       792
      Guelinviridae       0.00      0.00      0.00         1
     Herelleviridae       0.00      0.00      0.00         4
       Kyanoviridae       0.00      0.00      0.00         1
Mesyanzhinovviridae       0.00      0.00      0.00        36
  Orlajensenviridae       0.00      0.00      0.00        33
       Peduoviridae       0.98      0.31      0.48      1215
     Salasmaviridae       0.00      0.00      0.00         4
      Straboviridae       0.00      0.00      0.00        20
       Vilmaviridae       0.00      0.00      0.00         7
      Zierdtviridae       0.00      0.00      0.00        15

          micro avg       0.98      0.17      0.30      2195
          macro avg       0.07      0.02      0.03      2195
       weighted avg       0.54      0.17      0.26      2195


**Viral Class** Accuracy: 0.9467
Number of test samples: 2195
Number of classes in test: 1

Classification Report:
                precision    recall  f1-score   support

Caudoviricetes       1.00      0.95      0.97      2195

     micro avg       1.00      0.95      0.97      2195
     macro avg       1.00      0.95      0.97      2195
  weighted avg       1.00      0.95      0.97      2195


**Viral Phylum** Accuracy: 0.9462
Number of test samples: 2195
Number of classes in test: 1

Classification Report:
              precision    recall  f1-score   support

 Uroviricota       1.00      0.95      0.97      2195

   micro avg       1.00      0.95      0.97      2195
   macro avg       1.00      0.95      0.97      2195
weighted avg       1.00      0.95      0.97      2195


Warning: Found 20 unknown host Host_genus labels in test data:
Unknown labels: {'Pseudoclavibacter', 'Paraburkholderia', 'Rosenbergiella', 'Spirosoma', 'Dermacoccus', 'Paenarthrobacter', 'Aureimonas', 'Oceanobacillus', 'Pseudarthrobacter', 'Methylobacterium', 'Ewingella', 'Priestia', 'Methylopila', 'Frondihabitans', 'Frigoribacterium', 'Williamsia', 'Agromyces', 'Peribacillus', 'Belnapia', 'Pararhizobium'}
These samples will be excluded from evaluation

Host **Host_genus** Accuracy: 0.2068
Number of test samples: 2616
Number of classes in test: 21

Classification Report:
                precision    recall  f1-score   support

 Acinetobacter       0.92      0.55      0.69        20
  Arthrobacter       0.50      1.00      0.67         3
      Bacillus       0.88      0.58      0.70        12
 Brevundimonas       0.00      0.00      0.00        21
   Clavibacter       0.00      0.00      0.00         9
Curtobacterium       0.00      0.00      0.00        34
  Cytobacillus       0.00      0.00      0.00         4
       Erwinia       0.00      0.00      0.00      1143
Microbacterium       0.09      0.50      0.15         4
   Micrococcus       0.00      0.00      0.00         3
       Pantoea       0.00      0.00      0.00       138
    Paracoccus       0.00      0.00      0.00         9
   Pseudomonas       0.72      0.91      0.81       542
      Rahnella       0.00      0.00      0.00        89
     Ralstonia       0.00      0.00      0.00         2
 Rathayibacter       0.00      0.00      0.00        19
   Rhodococcus       0.00      0.00      0.00         1
      Serratia       0.00      0.00      0.00        24
  Sphingomonas       0.00      0.00      0.00       515
Staphylococcus       0.96      1.00      0.98        23
    Variovorax       0.00      0.00      0.00         1

     micro avg       0.62      0.21      0.31      2616
     macro avg       0.19      0.22      0.19      2616
  weighted avg       0.17      0.21      0.19      2616


Warning: Found 4 unknown host Host_family labels in test data:
Unknown labels: {'Dermacoccaceae', 'Cytophagaceae', 'Methylopilaceae', 'Methylobacteriaceae'}
These samples will be excluded from evaluation

Host **Host_family** Accuracy: 0.1794
Number of test samples: 3206
Number of classes in test: 17

Classification Report:
                   precision    recall  f1-score   support

 Acetobacteraceae       0.00      0.00      0.00         1
Aurantimonadaceae       0.00      0.00      0.00         3
      Bacillaceae       1.00      0.58      0.74        24
 Burkholderiaceae       0.00      0.00      0.00         4
 Caulobacteraceae       0.00      0.00      0.00        21
   Comamonadaceae       0.00      0.00      0.00         1
      Erwiniaceae       0.00      0.00      0.00      1777
Microbacteriaceae       0.94      0.36      0.52        90
   Micrococcaceae       0.45      0.28      0.34        18
    Moraxellaceae       0.92      0.60      0.73        20
     Nocardiaceae       0.00      0.00      0.00         6
    Paracoccaceae       0.00      0.00      0.00         9
 Pseudomonadaceae       0.74      0.88      0.81       542
     Rhizobiaceae       0.17      0.50      0.25         4
Sphingomonadaceae       0.00      0.00      0.00       515
Staphylococcaceae       0.92      1.00      0.96        23
     Yersiniaceae       0.10      0.07      0.08       148

        micro avg       0.53      0.18      0.27      3206
        macro avg       0.31      0.25      0.26      3206
     weighted avg       0.18      0.18      0.17      3206


Warning: Found 1 unknown host Host_order labels in test data:
Unknown labels: {'Cytophagales'}
These samples will be excluded from evaluation

Host **Host_order** Accuracy: 0.6804
Number of test samples: 3229
Number of classes in test: 12

Classification Report:
                  precision    recall  f1-score   support

      Bacillales       1.00      0.89      0.94        47
 Burkholderiales       0.00      0.20      0.01         5
 Caulobacterales       0.00      0.00      0.00        21
Enterobacterales       0.99      0.85      0.92      1925
Hyphomicrobiales       0.10      0.07      0.08        28
   Micrococcales       0.89      0.31      0.46       110
    Moraxellales       0.92      0.55      0.69        20
 Mycobacteriales       0.04      0.33      0.07         6
 Pseudomonadales       0.75      0.86      0.80       542
 Rhodobacterales       0.00      0.00      0.00         9
Rhodospirillales       0.00      0.00      0.00         1
Sphingomonadales       1.00      0.00      0.00       515

       micro avg       0.81      0.68      0.74      3229
       macro avg       0.47      0.34      0.33      3229
    weighted avg       0.93      0.68      0.72      3229


Warning: Found 1 unknown host Host_class labels in test data:
Unknown labels: {'Cytophagia'}
These samples will be excluded from evaluation

Host **Host_class** Accuracy: 0.8207
Number of test samples: 3229
Number of classes in test: 5

Classification Report:
                     precision    recall  f1-score   support

      Actinomycetes       0.66      0.71      0.68       116
Alphaproteobacteria       0.95      0.11      0.20       574
            Bacilli       1.00      0.91      0.96        47
 Betaproteobacteria       0.01      0.40      0.02         5
Gammaproteobacteria       0.97      0.99      0.98      2487

          micro avg       0.89      0.82      0.86      3229
          macro avg       0.72      0.62      0.57      3229
       weighted avg       0.96      0.82      0.83      3229


Host **Host_phylum** Accuracy: 0.9070
Number of test samples: 3238
Number of classes in test: 4

Classification Report:
                precision    recall  f1-score   support

Actinomycetota       0.65      0.72      0.68       116
     Bacillota       0.98      0.94      0.96        47
  Bacteroidota       0.00      0.00      0.00         9
Pseudomonadota       1.00      0.92      0.95      3066

     micro avg       0.98      0.91      0.94      3238
     macro avg       0.66      0.64      0.65      3238
  weighted avg       0.98      0.91      0.94      3238

#### train_millardmatrix; test_matrix

Train Accuracies: {'Genus': '0.8814', 'Sub-family': '0.9855', 'Family': '0.9065', 'Order': '0.9950', 'Class': '0.9981', 'Phylum': '0.9981', 'Kingdom': '0.9984', 'Host_genus': '0.8463', 'Host_family': '0.9043', 'Host_order': '0.9445', 'Host_class': '0.9771', 'Host_phylum': '0.9857'}
Val Accuracies: {'Genus': '0.9044', 'Sub-family': '0.9854', 'Family': '0.9003', 'Order': '0.9942', 'Class': '0.9975', 'Phylum': '0.9975', 'Kingdom': '0.9970', 'Host_genus': '0.8509', 'Host_family': '0.9072', 'Host_order': '0.9398', 'Host_class': '0.9734', 'Host_phylum': '0.9856'}

Number of test samples: 4181

**Viral Genus** Accuracy: 0.6667
Number of test samples: 12
Number of classes in test: 11

Classification Report:
                 precision    recall  f1-score   support

    Berlinvirus       0.00      0.00      0.00         1
     Dibbivirus       1.00      1.00      1.00         1
     Elunavirus       0.00      0.00      0.00         1
 Eracentumvirus       1.00      1.00      1.00         1
   Kayfunavirus       0.33      1.00      0.50         1
  Loessnervirus       0.00      0.00      0.00         1
    Murrayvirus       1.00      1.00      1.00         1
    Pahexavirus       1.00      1.00      1.00         1
Sauletekiovirus       0.00      0.00      0.00         1
   Sendosyvirus       1.00      1.00      1.00         1
    Uliginvirus       1.00      1.00      1.00         2

      micro avg       0.80      0.67      0.73        12
      macro avg       0.58      0.64      0.59        12
   weighted avg       0.61      0.67      0.62        12


**Viral Sub-family** Accuracy: 0.8571
Number of test samples: 7
Number of classes in test: 4

Classification Report:
                  precision    recall  f1-score   support

Cleopatravirinae       1.00      1.00      1.00         1
  Colwellvirinae       1.00      0.50      0.67         2
 Molineuxvirinae       1.00      1.00      1.00         1
  Studiervirinae       1.00      1.00      1.00         3

       micro avg       1.00      0.86      0.92         7
       macro avg       1.00      0.88      0.92         7
    weighted avg       1.00      0.86      0.90         7


**Viral Family** Accuracy: 0.4888
Number of test samples: 2459
Number of classes in test: 18

Classification Report:
                     precision    recall  f1-score   support

   Ackermannviridae       0.00      0.00      0.00         8
  Autographiviridae       0.51      0.31      0.38        91
     Casjensviridae       0.43      0.16      0.23       134
       Chaseviridae       0.33      0.19      0.24        67
     Demerecviridae       0.00      0.00      0.00         1
     Drexlerviridae       0.51      0.74      0.60       204
     Herelleviridae       0.17      0.07      0.10        15
       Kyanoviridae       0.12      0.02      0.04        42
Mesyanzhinovviridae       0.36      0.14      0.20       259
  Orlajensenviridae       0.40      0.52      0.45       312
       Peduoviridae       0.61      0.65      0.63       753
    Rountreeviridae       0.00      0.00      0.00         1
     Salasmaviridae       0.68      0.63      0.65        27
      Schitoviridae       0.40      0.21      0.27        29
      Straboviridae       0.50      0.11      0.18         9
       Vilmaviridae       0.48      0.57      0.52       314
      Zierdtviridae       0.39      0.52      0.44       174
      Zobellviridae       0.35      0.32      0.33        19

          micro avg       0.49      0.49      0.49      2459
          macro avg       0.35      0.29      0.29      2459
       weighted avg       0.48      0.49      0.47      2459


No valid test samples for **viral Order**

**Viral Class** Accuracy: 0.9988
Number of test samples: 2463
Number of classes in test: 1

Classification Report:
                precision    recall  f1-score   support

Caudoviricetes       1.00      1.00      1.00      2463

     micro avg       1.00      1.00      1.00      2463
     macro avg       1.00      1.00      1.00      2463
  weighted avg       1.00      1.00      1.00      2463


**Viral Phylum** Accuracy: 0.9988
Number of test samples: 2463
Number of classes in test: 1

Classification Report:
              precision    recall  f1-score   support

 Uroviricota       1.00      1.00      1.00      2463

   micro avg       1.00      1.00      1.00      2463
   macro avg       1.00      1.00      1.00      2463
weighted avg       1.00      1.00      1.00      2463


**Viral Kingdom** Accuracy: 1.0000
Number of test samples: 12
Number of classes in test: 1

Classification Report:
                precision    recall  f1-score   support

Heunggongvirae       1.00      1.00      1.00        12

      accuracy                           1.00        12
     macro avg       1.00      1.00      1.00        12
  weighted avg       1.00      1.00      1.00        12


Warning: Found 29 unknown host Host_genus labels in test data:
Unknown labels: {'Candidatus Regiella', 'Frondihabitans', 'Paraburkholderia', 'Pseudescherichia', 'Tenebrionibacter', 'Samsonia', 'Demequina', 'Epilithonimonas', 'Duganella', 'Arachnia', 'Sphingomicrobium', 'Leifsonia', 'Rouxiella', 'Oerskovia', 'Agreia', 'Porticoccus', 'Scandinavium', 'Ensifer', 'Subtercola', 'Smaragdicoccus', 'Leucobacter', 'Methylibium', 'Blastococcus', 'Kocuria', 'Maritimibacter', 'Sanguibacter', 'Pedomonas', 'Rickettsiella', 'Tamlana'}
These samples will be excluded from evaluation

Host **Host_genus** Accuracy: 0.5987
Number of test samples: 1565
Number of classes in test: 100

Classification Report:
                    precision    recall  f1-score   support

     Achromobacter       0.00      0.00      0.00         1
     Agrobacterium       0.40      0.29      0.33        14
         Agromyces       0.00      0.00      0.00         1
      Arsenophonus       0.00      0.00      0.00         1
      Arthrobacter       0.00      0.00      0.00         4
     Atlantibacter       0.00      0.00      0.00         1
        Aureimonas       0.00      0.00      0.00        13
          Bacillus       0.00      0.00      0.00         1
       Bacteroides       1.00      0.08      0.15        12
   Bifidobacterium       0.50      0.50      0.50         2
        Bordetella       0.00      0.00      0.00         1
    Bradyrhizobium       0.00      0.00      0.00         2
     Brevundimonas       0.00      0.00      0.00         2
      Buttiauxella       0.00      0.00      0.00         1
    Carnobacterium       0.00      0.00      0.00         1
Cellulosimicrobium       1.00      0.25      0.40         4
  Chryseobacterium       0.00      0.00      0.00         2
       Citrobacter       0.00      0.00      0.00         7
       Clavibacter       0.10      0.17      0.12         6
        Collimonas       0.00      0.00      0.00         1
       Collinsella       0.00      0.00      0.00         2
         Comamonas       0.00      0.00      0.00         2
   Corynebacterium       0.00      0.00      0.00         1
       Cronobacter       0.00      0.00      0.00         2
    Curtobacterium       0.42      0.28      0.34        53
     Cutibacterium       0.00      0.00      0.00         2
       Deinococcus       0.00      0.00      0.00         6
           Devosia       0.00      0.00      0.00         2
      Enterobacter       0.00      0.00      0.00        18
      Enterococcus       0.50      0.25      0.33         4
           Erwinia       0.17      0.02      0.03        54
       Escherichia       0.06      0.07      0.06        15
         Ewingella       0.00      0.00      0.00        11
   Exiguobacterium       1.00      0.50      0.67         2
  Frigoribacterium       0.08      0.06      0.07        18
  Geodermatophilus       0.00      0.00      0.00         1
          Gordonia       0.00      0.00      0.00         1
            Hafnia       0.47      0.35      0.40        20
         Halomonas       0.00      0.00      0.00         1
       Herbiconiux       0.00      0.00      0.00         9
      Hymenobacter       0.91      0.93      0.92       147
    Hyphomicrobium       0.00      0.00      0.00         1
        Izhakiella       0.00      0.00      0.00         1
        Klebsiella       0.02      0.09      0.03        11
           Klenkia       0.00      0.00      0.00         1
         Kosakonia       0.00      0.00      0.00         1
         Leclercia       0.00      0.00      0.00         3
       Marmoricola       0.00      0.00      0.00         2
         Megamonas       0.00      0.00      0.00         1
     Mesorhizobium       0.00      0.00      0.00         1
  Methylobacterium       0.57      0.71      0.63        59
    Microbacterium       0.12      0.20      0.15        10
        Microvirga       0.00      0.00      0.00         4
             Mixta       0.00      0.00      0.00         4
     Mycobacterium       0.37      0.59      0.46        56
      Neorhizobium       0.00      0.00      0.00         7
          Nocardia       0.00      0.00      0.00         2
      Nocardioides       0.00      0.00      0.00        17
            Nostoc       0.50      1.00      0.67         1
   Novosphingobium       0.00      0.00      0.00         3
      Ochrobactrum       0.00      0.00      0.00         1
           Pantoea       0.47      0.70      0.57       131
     Pararhizobium       0.00      0.00      0.00         2
      Pauljensenia       0.00      0.00      0.00         1
    Pectobacterium       0.00      0.00      0.00         1
        Pedobacter       0.50      0.50      0.50         2
       Phocaeicola       0.00      0.00      0.00         1
    Photobacterium       0.00      0.00      0.00         1
      Photorhabdus       0.00      0.00      0.00         5
      Plantibacter       0.00      0.00      0.00         6
        Pontimonas       0.00      0.00      0.00         1
        Prevotella       0.00      0.00      0.00         1
           Proteus       0.00      0.00      0.00         2
       Providencia       0.00      0.00      0.00         4
       Pseudomonas       0.87      0.95      0.91       271
   Pseudorhizobium       0.00      0.00      0.00         1
          Rahnella       0.11      0.09      0.10        23
     Rathayibacter       0.38      0.23      0.29        22
         Rhizobium       0.35      0.29      0.32        21
       Rhodococcus       0.42      0.23      0.29        22
    Rosenbergiella       0.12      0.25      0.17         4
 Ruminiclostridium       0.00      0.00      0.00         1
        Salmonella       0.08      0.20      0.12         5
          Serratia       0.00      0.00      0.00         7
          Shinella       0.00      0.00      0.00         1
     Sinorhizobium       0.00      0.00      0.00         2
           Sodalis       1.00      0.11      0.20         9
       Sphingobium       0.00      0.00      0.00         4
      Sphingomonas       0.84      0.98      0.90       315
  Stenotrophomonas       0.00      0.00      0.00         6
      Streptomyces       0.29      0.33      0.31        12
     Stutzerimonas       0.00      0.00      0.00         5
          Telluria       0.00      0.00      0.00         7
 Thermophilibacter       0.00      0.00      0.00         2
        Variovorax       0.50      0.13      0.21        15
            Vibrio       0.00      0.00      0.00         1
        Williamsia       0.00      0.00      0.00         1
       Xenorhabdus       0.00      0.00      0.00         1
        Xylophilus       0.00      0.00      0.00         3
          Yersinia       0.00      0.00      0.00        12

         micro avg       0.62      0.60      0.61      1565
         macro avg       0.14      0.11      0.11      1565
      weighted avg       0.56      0.60      0.56      1565


Warning: Found 6 unknown host Host_family labels in test data:
Unknown labels: {'Sphingosinicellaceae', 'Demequinaceae', 'Cellulomonadaceae', 'Coxiellaceae', 'Sanguibacteraceae', 'Porticoccaceae'}
These samples will be excluded from evaluation

Host **Host_family** Accuracy: 0.6711
Number of test samples: 1587
Number of classes in test: 55

Classification Report:
                       precision    recall  f1-score   support

     Actinomycetaceae       0.00      0.00      0.00         1
       Alcaligenaceae       0.00      0.00      0.00         2
         Atopobiaceae       0.00      0.00      0.00         2
    Aurantimonadaceae       0.00      0.00      0.00        13
          Bacillaceae       0.00      0.00      0.00         1
       Bacteroidaceae       1.00      0.08      0.14        13
   Bifidobacteriaceae       0.50      0.50      0.50         2
         Brucellaceae       0.00      0.00      0.00         1
  Bruguierivoracaceae       0.00      0.00      0.00         9
     Burkholderiaceae       0.05      1.00      0.09         1
    Carnobacteriaceae       0.00      0.00      0.00         1
     Caulobacteraceae       0.00      0.00      0.00         2
       Comamonadaceae       0.00      0.00      0.00        17
    Coriobacteriaceae       0.00      0.00      0.00         2
   Corynebacteriaceae       0.00      0.00      0.00         1
       Deinococcaceae       0.00      0.00      0.00         6
          Devosiaceae       0.00      0.00      0.00         2
   Enterobacteriaceae       0.22      0.45      0.29        69
      Enterococcaceae       0.50      0.25      0.33         4
          Erwiniaceae       0.64      0.57      0.60       194
    Flavobacteriaceae       1.00      1.00      1.00         1
  Geodermatophilaceae       0.14      0.33      0.20         3
         Gordoniaceae       0.00      0.00      0.00         1
           Hafniaceae       0.55      0.30      0.39        20
       Halomonadaceae       0.00      0.00      0.00         1
    Hymenobacteraceae       0.91      0.94      0.93       147
    Hyphomicrobiaceae       0.00      0.00      0.00         1
      Lysobacteraceae       0.50      0.17      0.25         6
  Methylobacteriaceae       0.63      0.68      0.66        63
    Microbacteriaceae       0.72      0.65      0.69       132
       Micrococcaceae       0.00      0.00      0.00         5
       Morganellaceae       1.00      0.08      0.14        13
     Mycobacteriaceae       0.43      0.52      0.47        56
     Nitrobacteraceae       0.00      0.00      0.00         2
         Nocardiaceae       0.55      0.23      0.32        26
      Nocardioidaceae       0.20      0.05      0.08        19
          Nostocaceae       0.00      0.00      0.00         1
     Oscillospiraceae       0.00      0.00      0.00         1
     Oxalobacteraceae       0.00      0.00      0.00        11
    Pectobacteriaceae       0.00      0.00      0.00         2
   Phyllobacteriaceae       0.00      0.00      0.00         1
       Prevotellaceae       0.00      0.00      0.00         1
Promicromonosporaceae       0.00      0.00      0.00         4
 Propionibacteriaceae       0.29      0.67      0.40         3
     Pseudomonadaceae       0.89      0.95      0.92       276
         Rhizobiaceae       0.74      0.47      0.57        49
     Roseobacteraceae       0.00      0.00      0.00         1
     Selenomonadaceae       0.00      0.00      0.00         1
      Sphaerotilaceae       0.00      0.00      0.00         1
  Sphingobacteriaceae       0.00      0.00      0.00         2
    Sphingomonadaceae       0.85      0.96      0.90       323
    Streptomycetaceae       0.31      0.33      0.32        12
         Vibrionaceae       0.00      0.00      0.00         2
        Weeksellaceae       0.00      0.00      0.00         3
         Yersiniaceae       0.23      0.09      0.13        54

            micro avg       0.68      0.67      0.68      1587
            macro avg       0.23      0.20      0.19      1587
         weighted avg       0.67      0.67      0.66      1587


Warning: Found 2 unknown host Host_order labels in test data:
Unknown labels: {'Legionellales', 'Cellvibrionales'}
These samples will be excluded from evaluation

Host **Host_order** Accuracy: 0.8217
Number of test samples: 1598
Number of classes in test: 28

Classification Report:
                     precision    recall  f1-score   support

    Actinomycetales       0.00      0.00      0.00         1
         Bacillales       0.29      0.67      0.40         3
      Bacteroidales       0.33      0.07      0.12        14
  Bifidobacteriales       0.50      0.50      0.50         2
    Burkholderiales       0.55      0.49      0.52        35
    Caulobacterales       0.00      0.00      0.00         2
   Coriobacteriales       1.00      0.25      0.40         4
       Cytophagales       0.91      0.93      0.92       147
      Deinococcales       0.00      0.00      0.00         6
   Enterobacterales       0.97      0.96      0.97       361
      Eubacteriales       0.00      0.00      0.00         1
   Flavobacteriales       1.00      0.25      0.40         4
 Geodermatophilales       0.20      0.33      0.25         3
   Hyphomicrobiales       0.79      0.62      0.69       132
   Kitasatosporales       0.29      0.33      0.31        12
    Lactobacillales       0.40      0.40      0.40         5
     Lysobacterales       0.50      0.17      0.25         6
      Micrococcales       0.68      0.69      0.69       146
    Mycobacteriales       0.53      0.55      0.54        84
         Nostocales       1.00      1.00      1.00         1
  Oceanospirillales       0.00      0.00      0.00         1
Propionibacteriales       0.33      0.14      0.19        22
    Pseudomonadales       0.90      0.94      0.92       276
    Rhodobacterales       0.00      0.00      0.00         1
    Selenomonadales       0.00      0.00      0.00         1
 Sphingobacteriales       0.00      0.00      0.00         2
   Sphingomonadales       0.85      0.95      0.90       324
        Vibrionales       0.00      0.00      0.00         2

          micro avg       0.83      0.82      0.83      1598
          macro avg       0.43      0.37      0.37      1598
       weighted avg       0.82      0.82      0.82      1598


Host **Host_class** Accuracy: 0.9287
Number of test samples: 1600
Number of classes in test: 14

Classification Report:
                     precision    recall  f1-score   support

      Actinomycetes       0.96      0.96      0.96       270
Alphaproteobacteria       0.94      0.95      0.94       459
            Bacilli       0.73      1.00      0.84         8
        Bacteroidia       0.50      0.07      0.12        14
 Betaproteobacteria       0.61      0.40      0.48        35
         Clostridia       0.00      0.00      0.00         1
     Coriobacteriia       1.00      0.50      0.67         4
       Cyanophyceae       0.17      1.00      0.29         1
         Cytophagia       0.91      0.93      0.92       147
         Deinococci       0.00      0.00      0.00         6
     Flavobacteriia       1.00      0.25      0.40         4
Gammaproteobacteria       0.95      0.97      0.96       648
      Negativicutes       0.00      0.00      0.00         1
   Sphingobacteriia       0.00      0.00      0.00         2

          micro avg       0.93      0.93      0.93      1600
          macro avg       0.55      0.50      0.47      1600
       weighted avg       0.92      0.93      0.92      1600


Host **Host_phylum** Accuracy: 0.9675
Number of test samples: 1600
Number of classes in test: 6

Classification Report:
                 precision    recall  f1-score   support

 Actinomycetota       0.96      0.96      0.96       274
      Bacillota       0.60      0.90      0.72        10
   Bacteroidota       0.97      0.90      0.93       167
Cyanobacteriota       0.17      1.00      0.29         1
   Deinococcota       0.00      0.00      0.00         6
 Pseudomonadota       0.98      0.99      0.98      1142

      micro avg       0.97      0.97      0.97      1600
      macro avg       0.61      0.79      0.65      1600
   weighted avg       0.97      0.97      0.97      1600

#### train_millardstrain; test_strain

Train Loss: 0.2000, Val Loss: 0.3548
Train Accuracies: {'Family': '0.9851', 'Order': '0.9987', 'Class': '0.9991', 'Phylum': '0.9991', 'Host_genus': '0.8733', 'Host_family': '0.9277', 'Host_order': '0.9579', 'Host_class': '0.9826', 'Host_phylum': '0.9889'}
Val Accuracies: {'Family': '0.9840', 'Order': '0.9953', 'Class': '0.9979', 'Phylum': '0.9975', 'Host_genus': '0.8706', 'Host_family': '0.9253', 'Host_order': '0.9567', 'Host_class': '0.9793', 'Host_phylum': '0.9885'}

Number of test samples: 1618

**Viral Family** Accuracy: 0.9290
Number of test samples: 1113
Number of classes in test: 15

Classification Report:
                     precision    recall  f1-score   support

   Ackermannviridae       1.00      0.67      0.80         3
  Autographiviridae       0.60      0.60      0.60         5
     Casjensviridae       0.57      0.29      0.38        14
       Chaseviridae       1.00      0.75      0.86         8
     Drexlerviridae       0.99      0.92      0.95       417
      Guelinviridae       0.00      0.00      0.00         1
     Herelleviridae       0.50      0.33      0.40         3
       Kyanoviridae       0.00      0.00      0.00         1
Mesyanzhinovviridae       0.47      0.41      0.44        17
  Orlajensenviridae       0.92      0.71      0.80        17
       Peduoviridae       0.92      0.98      0.95       609
     Salasmaviridae       1.00      1.00      1.00         1
      Straboviridae       1.00      1.00      1.00         8
       Vilmaviridae       0.25      0.33      0.29         3
      Zierdtviridae       0.55      1.00      0.71         6

          micro avg       0.93      0.93      0.93      1113
          macro avg       0.65      0.60      0.61      1113
       weighted avg       0.93      0.93      0.93      1113


No valid test samples for viral Order

**Viral Class** Accuracy: 0.9973
Number of test samples: 1113
Number of classes in test: 1

Classification Report:
                precision    recall  f1-score   support

Caudoviricetes       1.00      1.00      1.00      1113

     micro avg       1.00      1.00      1.00      1113
     macro avg       1.00      1.00      1.00      1113
  weighted avg       1.00      1.00      1.00      1113


**Viral Phylum** Accuracy: 0.9973
Number of test samples: 1113
Number of classes in test: 1

Classification Report:
              precision    recall  f1-score   support

 Uroviricota       1.00      1.00      1.00      1113

   micro avg       1.00      1.00      1.00      1113
   macro avg       1.00      1.00      1.00      1113
weighted avg       1.00      1.00      1.00      1113


Warning: Found 4 unknown host Host_genus labels in test data:
Unknown labels: {'Aureimonas', 'Belnapia', 'Dermacoccus', 'Priestia'}
These samples will be excluded from evaluation

##### using ground truth host taxonomy in testing

Host **Host_genus** Accuracy: 0.8975
Number of test samples: 1610
Number of classes in test: 36

Classification Report:
                   precision    recall  f1-score   support

    Acinetobacter       0.73      1.00      0.84         8
        Agromyces       0.00      0.00      0.00         1
     Arthrobacter       0.33      1.00      0.50         2
         Bacillus       0.43      0.75      0.55         4
    Brevundimonas       0.50      1.00      0.67        10
      Clavibacter       0.00      0.00      0.00         2
   Curtobacterium       0.73      0.50      0.59        16
     Cytobacillus       0.00      0.00      0.00         4
          Erwinia       0.96      0.96      0.96       561
        Ewingella       0.63      0.92      0.75        13
 Frigoribacterium       0.33      0.60      0.43         5
   Frondihabitans       0.00      0.00      0.00         3
 Methylobacterium       0.50      0.29      0.36         7
      Methylopila       0.00      0.00      0.00         3
   Microbacterium       0.00      0.00      0.00         3
      Micrococcus       0.00      0.00      0.00         1
   Oceanobacillus       0.00      0.00      0.00         1
 Paenarthrobacter       0.00      0.00      0.00         2
          Pantoea       0.64      0.64      0.64        64
 Paraburkholderia       0.00      0.00      0.00         1
       Paracoccus       0.33      0.17      0.22         6
    Pararhizobium       0.00      0.00      0.00         2
     Peribacillus       1.00      0.50      0.67         2
Pseudarthrobacter       1.00      0.20      0.33         5
      Pseudomonas       0.97      0.97      0.97       270
         Rahnella       0.76      0.57      0.65        46
        Ralstonia       0.00      0.00      0.00         1
    Rathayibacter       0.50      0.43      0.46         7
      Rhodococcus       0.00      0.00      0.00         1
   Rosenbergiella       0.99      0.98      0.99       271
         Serratia       0.00      0.00      0.00        12
     Sphingomonas       0.96      0.96      0.96       255
        Spirosoma       1.00      0.50      0.67         6
   Staphylococcus       1.00      1.00      1.00        11
       Variovorax       0.00      0.00      0.00         1
       Williamsia       0.25      0.33      0.29         3

        micro avg       0.92      0.90      0.91      1610
        macro avg       0.40      0.40      0.37      1610
     weighted avg       0.91      0.90      0.90      1610


Warning: Found 1 unknown host Host_family labels in test data:
Unknown labels: {'Dermacoccaceae'}
These samples will be excluded from evaluation

Host **Host_family** Accuracy: 0.9344
Number of test samples: 1616
Number of classes in test: 20

Classification Report:
                     precision    recall  f1-score   support

   Acetobacteraceae       0.00      0.00      0.00         1
  Aurantimonadaceae       0.00      0.00      0.00         3
        Bacillaceae       1.00      0.54      0.70        13
   Burkholderiaceae       0.00      0.00      0.00         2
   Caulobacteraceae       0.62      1.00      0.77        10
     Comamonadaceae       0.00      0.00      0.00         1
      Cytophagaceae       1.00      0.50      0.67         6
        Erwiniaceae       0.99      0.97      0.98       896
Methylobacteriaceae       0.50      0.43      0.46         7
    Methylopilaceae       0.00      0.00      0.00         3
  Microbacteriaceae       0.91      0.78      0.84        37
     Micrococcaceae       0.53      0.80      0.64        10
      Moraxellaceae       0.73      1.00      0.84         8
       Nocardiaceae       0.43      0.75      0.55         4
      Paracoccaceae       0.12      0.17      0.14         6
   Pseudomonadaceae       0.98      0.98      0.98       270
       Rhizobiaceae       0.33      0.50      0.40         2
  Sphingomonadaceae       0.96      0.95      0.95       255
  Staphylococcaceae       1.00      1.00      1.00        11
       Yersiniaceae       0.77      0.76      0.77        71

          micro avg       0.95      0.93      0.94      1616
          macro avg       0.54      0.56      0.53      1616
       weighted avg       0.95      0.93      0.94      1616


Host **Host_order** Accuracy: 0.9617
Number of test samples: 1618
Number of classes in test: 13

Classification Report:
                  precision    recall  f1-score   support

      Bacillales       1.00      0.92      0.96        24
 Burkholderiales       0.00      0.00      0.00         3
 Caulobacterales       0.67      1.00      0.80        10
    Cytophagales       1.00      0.50      0.67         6
Enterobacterales       1.00      0.99      0.99       967
Hyphomicrobiales       0.33      0.07      0.11        15
   Micrococcales       0.79      0.94      0.86        49
    Moraxellales       0.73      1.00      0.84         8
 Mycobacteriales       0.00      0.00      0.00         4
 Pseudomonadales       0.97      0.97      0.97       270
 Rhodobacterales       0.42      0.83      0.56         6
Rhodospirillales       0.00      0.00      0.00         1
Sphingomonadales       0.96      0.95      0.95       255

       micro avg       0.97      0.96      0.96      1618
       macro avg       0.61      0.63      0.59      1618
    weighted avg       0.97      0.96      0.96      1618


Host **Host_class** Accuracy: 0.9858
Number of test samples: 1618
Number of classes in test: 6

Classification Report:
                     precision    recall  f1-score   support

      Actinomycetes       0.90      0.98      0.94        53
Alphaproteobacteria       0.97      0.98      0.97       287
            Bacilli       1.00      0.96      0.98        24
 Betaproteobacteria       0.00      0.00      0.00         3
         Cytophagia       1.00      0.50      0.67         6
Gammaproteobacteria       1.00      0.99      1.00      1245

          micro avg       0.99      0.99      0.99      1618
          macro avg       0.81      0.74      0.76      1618
       weighted avg       0.99      0.99      0.99      1618


Host **Host_phylum** Accuracy: 0.9883
Number of test samples: 1618
Number of classes in test: 4

Classification Report:
                precision    recall  f1-score   support

Actinomycetota       0.84      0.98      0.90        53
     Bacillota       1.00      1.00      1.00        24
  Bacteroidota       1.00      0.17      0.29         6
Pseudomonadota       1.00      0.99      0.99      1535

     micro avg       0.99      0.99      0.99      1618
     macro avg       0.96      0.78      0.80      1618
  weighted avg       0.99      0.99      0.99      1618

##### using iphop host taxonomy in testing

Warning: Found 17 unknown host Host_genus labels in test data:
Unknown labels: {'Phaseolibacter', 'Xenorhabdus', 'Photorhabdus', 'Lonsdalea', 'Luteimonas', 'Priestia', 'Rouxiella', 'Promicromonospora', 'Tatumella', 'Pseudacidovorax', 'Atlantibacter', 'Belnapia', 'Aureimonas', 'Pluralibacter', 'Dermacoccus', 'Mixta', 'Kocuria'}
These samples will be excluded from evaluation

Host Host_genus Accuracy: 0.6882
Number of test samples: 1408
Number of classes in test: 43

Classification Report:
                  precision    recall  f1-score   support

   Acinetobacter       0.73      0.89      0.80         9
    Arthrobacter       0.40      1.00      0.57         2
        Bacillus       0.43      0.75      0.55         4
   Brevundimonas       0.60      1.00      0.75         9
     Cronobacter       0.00      0.00      0.00         1
  Curtobacterium       0.80      0.50      0.62        16
    Cytobacillus       0.00      0.00      0.00         4
         Dickeya       0.00      0.00      0.00         5
    Enterobacter       0.00      0.00      0.00        62
         Erwinia       0.55      0.96      0.70       290
     Escherichia       0.00      0.00      0.00       144
       Ewingella       0.23      0.16      0.19        19
Frigoribacterium       0.43      1.00      0.60         3
  Frondihabitans       0.00      0.00      0.00         1
        Gordonia       0.00      0.00      0.00         2
      Klebsiella       0.00      0.00      0.00         5
      Lelliottia       0.00      0.00      0.00         1
Methylobacterium       0.50      0.20      0.29         5
     Methylopila       0.00      0.00      0.00         2
  Microbacterium       0.00      0.00      0.00         1
  Oceanobacillus       0.00      0.00      0.00         1
Paenarthrobacter       1.00      0.50      0.67         6
         Pantoea       0.61      0.42      0.50        84
Paraburkholderia       0.00      0.00      0.00         1
      Paracoccus       0.33      0.33      0.33         3
   Pararhizobium       0.00      0.00      0.00         1
  Pectobacterium       0.00      0.00      0.00         1
    Peribacillus       1.00      0.50      0.67         2
     Providencia       0.00      0.00      0.00         3
     Pseudomonas       1.00      0.97      0.98       269
        Rahnella       0.32      0.34      0.33        29
       Ralstonia       0.00      0.00      0.00         1
   Rathayibacter       0.67      0.40      0.50         5
       Rhizobium       0.50      1.00      0.67         1
     Rhodococcus       0.00      0.00      0.00         1
  Rosenbergiella       0.61      0.99      0.75       138
      Salmonella       0.00      0.00      0.00         8
        Serratia       0.00      0.00      0.00        10
    Sphingomonas       0.96      0.96      0.96       199
  Staphylococcus       1.00      1.00      1.00        11
    Streptomyces       0.00      0.00      0.00         2
      Williamsia       0.25      1.00      0.40         1
        Yersinia       0.00      0.00      0.00        46

       micro avg       0.70      0.69      0.69      1408
       macro avg       0.30      0.35      0.30      1408
    weighted avg       0.59      0.69      0.62      1408


Warning: Found 1 unknown host Host_family labels in test data:
Unknown labels: {'Dermacoccaceae'}
These samples will be excluded from evaluation

Host Host_family Accuracy: 0.7182
Number of test samples: 1501
Number of classes in test: 26

Classification Report:
                       precision    recall  f1-score   support

     Acetobacteraceae       0.00      0.00      0.00         1
    Aurantimonadaceae       0.00      0.00      0.00         3
          Bacillaceae       1.00      0.58      0.74        12
     Burkholderiaceae       0.00      0.00      0.00         2
     Caulobacteraceae       0.75      1.00      0.86         9
       Comamonadaceae       0.00      0.00      0.00         1
   Enterobacteriaceae       0.20      0.00      0.01       246
          Erwiniaceae       0.59      0.97      0.74       525
         Gordoniaceae       0.00      0.00      0.00         2
      Lysobacteraceae       0.00      0.00      0.00         4
  Methylobacteriaceae       0.40      0.40      0.40         5
      Methylopilaceae       0.00      0.00      0.00         2
    Microbacteriaceae       0.82      0.88      0.85        26
       Micrococcaceae       0.80      0.89      0.84         9
        Moraxellaceae       0.73      0.89      0.80         9
       Morganellaceae       0.00      0.00      0.00        32
         Nocardiaceae       0.14      0.50      0.22         2
        Paracoccaceae       0.12      0.33      0.18         3
    Pectobacteriaceae       0.00      0.00      0.00         7
Promicromonosporaceae       0.00      0.00      0.00         1
     Pseudomonadaceae       0.99      0.98      0.99       269
         Rhizobiaceae       0.50      0.50      0.50         2
    Sphingomonadaceae       0.96      0.95      0.96       199
    Staphylococcaceae       1.00      1.00      1.00        11
    Streptomycetaceae       0.00      0.00      0.00         2
         Yersiniaceae       0.74      0.38      0.51       117

            micro avg       0.73      0.72      0.72      1501
            macro avg       0.38      0.39      0.37      1501
         weighted avg       0.65      0.72      0.65      1501


Host Host_order Accuracy: 0.9641
Number of test samples: 1503
Number of classes in test: 14

Classification Report:
                  precision    recall  f1-score   support

      Bacillales       1.00      0.96      0.98        23
 Burkholderiales       0.00      0.00      0.00         3
 Caulobacterales       0.75      1.00      0.86         9
Enterobacterales       0.99      0.99      0.99       927
Hyphomicrobiales       0.50      0.08      0.14        12
Kitasatosporales       0.00      0.00      0.00         2
  Lysobacterales       0.00      0.00      0.00         4
   Micrococcales       0.80      0.95      0.87        38
    Moraxellales       0.73      0.89      0.80         9
 Mycobacteriales       0.00      0.00      0.00         4
 Pseudomonadales       0.99      0.97      0.98       269
 Rhodobacterales       0.22      0.67      0.33         3
Rhodospirillales       0.00      0.00      0.00         1
Sphingomonadales       0.96      0.96      0.96       199

       micro avg       0.97      0.96      0.97      1503
       macro avg       0.50      0.53      0.49      1503
    weighted avg       0.97      0.96      0.96      1503


Host Host_class Accuracy: 0.9887
Number of test samples: 1503
Number of classes in test: 5

Classification Report:
                     precision    recall  f1-score   support

      Actinomycetes       0.90      1.00      0.95        44
Alphaproteobacteria       0.96      0.98      0.97       224
            Bacilli       1.00      1.00      1.00        23
 Betaproteobacteria       0.00      0.00      0.00         3
Gammaproteobacteria       1.00      0.99      1.00      1209

          micro avg       0.99      0.99      0.99      1503
          macro avg       0.77      0.79      0.78      1503
       weighted avg       0.99      0.99      0.99      1503


Host Host_phylum Accuracy: 0.9927
Number of test samples: 1503
Number of classes in test: 3

Classification Report:
                precision    recall  f1-score   support

Actinomycetota       0.85      1.00      0.92        44
     Bacillota       1.00      1.00      1.00        23
Pseudomonadota       1.00      0.99      1.00      1436

     micro avg       0.99      0.99      0.99      1503
     macro avg       0.95      1.00      0.97      1503
  weighted avg       1.00      0.99      0.99      1503



#### train_strain; test_matrix

Original embeddings count: 3238
Matched embeddings count: 3238
Percentage retained: 100.00%
Family: 16 classes
Class: 2 classes
Phylum: 2 classes
Host_genus: 41 classes
Host_family: 21 classes
Host_order: 13 classes
Host_class: 6 classes
Host_phylum: 4 classes

Train Loss: 0.0442, Val Loss: 0.0540
Train Accuracies: {'Family': '0.9846', 'Class': '1.0000', 'Phylum': '1.0000', 'Host_genus': '0.9749', 'Host_family': '0.9935', 'Host_order': '0.9963', 'Host_class': '0.9986', 'Host_phylum': '0.9983'}
Val Accuracies: {'Family': '0.9750', 'Class': '1.0000', 'Phylum': '1.0000', 'Host_genus': '0.9896', 'Host_family': '0.9948', 'Host_order': '1.0000', 'Host_class': '1.0000', 'Host_phylum': '1.0000'}

Number of test samples: 8360

Warning: Found 4 unknown viral Family labels in test data:
Unknown labels: {'Zobellviridae', 'Demerecviridae', 'Schitoviridae', 'Rountreeviridae'}
These samples will be excluded from evaluation

Viral Family Accuracy: 0.3183
Number of test samples: 4775
Number of classes in test: 14

Classification Report:
                     precision    recall  f1-score   support

   Ackermannviridae       0.00      0.00      0.00        17
  Autographiviridae       0.00      0.00      0.00       168
     Casjensviridae       0.00      0.00      0.00       303
       Chaseviridae       0.00      0.00      0.00       131
     Drexlerviridae       0.43      0.31      0.36       390
     Herelleviridae       0.00      0.00      0.00        30
       Kyanoviridae       0.00      0.00      0.00        76
Mesyanzhinovviridae       0.32      0.01      0.02       520
  Orlajensenviridae       0.00      0.00      0.00       613
       Peduoviridae       0.31      0.94      0.47      1487
     Salasmaviridae       0.00      0.00      0.00        66
      Straboviridae       0.00      0.00      0.00        21
       Vilmaviridae       0.00      0.00      0.00       617
      Zierdtviridae       0.00      0.00      0.00       336

           accuracy                           0.32      4775
          macro avg       0.08      0.09      0.06      4775
       weighted avg       0.17      0.32      0.18      4775


Viral Class Accuracy: 1.0000
Number of test samples: 4894
Number of classes in test: 1

Classification Report:
                precision    recall  f1-score   support

Caudoviricetes       1.00      1.00      1.00      4894

      accuracy                           1.00      4894
     macro avg       1.00      1.00      1.00      4894
  weighted avg       1.00      1.00      1.00      4894


Viral Phylum Accuracy: 1.0000
Number of test samples: 4894
Number of classes in test: 1

Classification Report:
              precision    recall  f1-score   support

 Uroviricota       1.00      1.00      1.00      4894

    accuracy                           1.00      4894
   macro avg       1.00      1.00      1.00      4894
weighted avg       1.00      1.00      1.00      4894


Warning: Found 144 unknown host Host_genus labels in test data:
Unknown labels: {'Pelagerythrobacter', 'Porticoccus', 'Samsonia', 'Xylophilus', 'Subtercola', 'Demequina', 'Phaseolibacter', 'Collinsella', 'Maritimibacter', 'Bifidobacterium', 'Phyllobacterium', 'Citrobacter', 'Ruminococcus', 'Pseudorhizobium', 'Megamonas', 'Thermophilibacter', 'Chryseobacterium', 'Methyloglobulus', 'Parasynechococcus', 'Mesorhizobium', 'Marmoricola', 'Candidatus Flexicrinis', 'Hyphomicrobium', 'Corynebacterium', 'Leclercia', 'Halomonas', 'Plantibacter', 'Cronobacter', 'Photorhabdus', 'Promicromonospora', 'Prevotella', 'Blastococcus', 'Pedobacter', 'Atlantibacter', 'Duganella', 'Pectobacterium', 'Providencia', 'Vibrio', 'Agrobacterium', 'Neorhizobium', 'Ensifer', 'Methylibium', 'Sanguibacter', 'Pluralibacter', 'Gordonia', 'Nocardia', 'Leifsonia', 'Comamonas', 'Pseudoxanthomonas', 'Escherichia', 'Pontimonas', 'Enterobacter', 'Alloprevotella', 'Candidatus Scatomonas', 'Izhakiella', 'Kibdelosporangium', 'Candidatus Regiella', 'Xanthomonas', 'Cutibacterium', 'Sodalis', 'Sphingomicrobium', 'Nostoc', 'Nocardioides', 'Xenorhabdus', 'Yersinia', 'Faecalibacterium', 'Rickettsiella', 'Fictibacillus', 'Bradyrhizobium', 'Rhizobium', 'Pseudonocardia', 'Acidovorax', 'Alistipes', 'Aminobacter', 'Novosphingobium', 'Janthinobacterium', 'Cellulosimicrobium', 'Enterococcus', 'Sinorhizobium', 'Ochrobactrum', 'Kocuria', 'Ruminiclostridium', 'Flavobacterium', 'Erythrobacter', 'Mycoplana', 'Agreia', 'Phocaeicola', 'Hafnia', 'Arachnia', 'Pseudescherichia', 'Bordetella', 'Candidatus Microsaccharimonas', 'Leucobacter', 'Collimonas', 'Carnobacterium', 'Epilithonimonas', 'Rouxiella', 'Xenophilus', 'Aurantimonas', 'Salmonella', 'Sphingopyxis', 'Microvirga', 'Geodermatophilus', 'Scandinavium', 'Afipia', 'Nitrospira', 'Pauljensenia', 'Microcoleus', 'Stutzerimonas', 'Polynucleobacter', 'Herbiconiux', 'Shinella', 'Exiguobacterium', 'Aquibium', 'Hymenobacter', 'Smaragdicoccus', 'Devosia', 'Pedomonas', 'Proteus', 'Tamlana', 'Stenotrophomonas', 'Klebsiella', 'Cupriavidus', 'Cryobacterium', 'Candidatus Stercorousia', 'Kosakonia', 'Bacteroides', 'Tenebrionibacter', 'Achromobacter', 'Mycobacterium', 'Streptomyces', 'Candidatus Hamiltonella', 'Morganella', 'Mixta', 'Telluria', 'Actinosynnema', 'Deinococcus', 'Sphingobium', 'Arsenophonus', 'Mediterraneibacter', 'Photobacterium', 'Buttiauxella', 'Oerskovia', 'Klenkia'}
These samples will be excluded from evaluation

Host Host_genus Accuracy: 0.5530
Number of test samples: 2121
Number of classes in test: 28

Classification Report:
                  precision    recall  f1-score   support

   Acinetobacter       0.00      0.00      0.00         4
       Agromyces       0.00      0.00      0.00         4
    Arthrobacter       0.00      0.00      0.00         9
      Aureimonas       0.00      0.00      0.00        28
        Bacillus       0.00      0.00      0.00         1
   Brevundimonas       0.00      0.00      0.00         3
     Clavibacter       0.00      0.00      0.00        13
  Curtobacterium       0.00      0.00      0.00        96
         Erwinia       0.26      0.16      0.20        97
       Ewingella       0.00      0.00      0.00        17
Frigoribacterium       0.00      0.00      0.00        32
  Frondihabitans       0.00      0.00      0.00         1
Methylobacterium       0.09      0.02      0.04       122
  Microbacterium       0.00      0.00      0.00        23
Paenarthrobacter       0.00      0.00      0.00         5
         Pantoea       0.65      0.20      0.31       252
Paraburkholderia       0.00      0.00      0.00         1
   Pararhizobium       0.00      0.00      0.00         6
     Pseudomonas       0.54      0.95      0.69       561
        Rahnella       0.00      0.00      0.00        44
   Rathayibacter       0.00      0.00      0.00        44
     Rhodococcus       0.00      0.00      0.00        42
  Rosenbergiella       0.50      0.44      0.47         9
        Serratia       0.00      0.00      0.00        17
    Sphingomonas       0.60      0.86      0.71       655
       Spirosoma       0.00      0.00      0.00         1
      Variovorax       0.00      0.00      0.00        28
      Williamsia       0.00      0.00      0.00         6

       micro avg       0.55      0.55      0.55      2121
       macro avg       0.09      0.09      0.09      2121
    weighted avg       0.42      0.55      0.45      2121


Warning: Found 58 unknown host Host_family labels in test data:
Unknown labels: {'Bifidobacteriaceae', 'Propionibacteriaceae', 'Nitrospiraceae', 'Enterococcaceae', 'Lachnospiraceae', 'Coxiellaceae', 'Hyphomicrobiaceae', 'Demequinaceae', 'Lysobacteraceae', 'Bruguierivoracaceae', 'Sanguibacteraceae', 'Bacteroidaceae', 'Brucellaceae', 'Weeksellaceae', 'Fusobacteriaceae', 'Rikenellaceae', 'Actinomycetaceae', 'Deinococcaceae', 'Morganellaceae', 'Nitrobacteraceae', 'Cellulomonadaceae', 'Pseudonocardiaceae', 'Devosiaceae', 'Alcaligenaceae', 'Hymenobacteraceae', 'Vibrionaceae', 'Porticoccaceae', 'Sphingosinicellaceae', 'Geodermatophilaceae', 'Microcoleaceae', 'Hafniaceae', 'Flavobacteriaceae', 'Roseobacteraceae', 'Candidatus Flexifilaceae', 'Selenomonadaceae', 'Streptomycetaceae', 'Sphingobacteriaceae', 'Phyllobacteriaceae', 'Carnobacteriaceae', 'Prevotellaceae', 'Nocardioidaceae', 'Atopobiaceae', 'Gordoniaceae', 'Coriobacteriaceae', 'Pectobacteriaceae', 'Mycobacteriaceae', 'Sphaerotilaceae', 'Halomonadaceae', 'Oscillospiraceae', 'Corynebacteriaceae', 'Erythrobacteraceae', 'Methylococcaceae', 'Promicromonosporaceae', 'Oxalobacteraceae', 'Prochlorococcaceae', 'Nostocaceae', 'Enterobacteriaceae', 'Candidatus Saccharimonadaceae'}
These samples will be excluded from evaluation

Host Host_family Accuracy: 0.5425
Number of test samples: 2365
Number of classes in test: 16

Classification Report:
                     precision    recall  f1-score   support

  Aurantimonadaceae       0.00      0.00      0.00        29
        Bacillaceae       0.00      0.00      0.00         2
   Burkholderiaceae       0.00      0.00      0.00         3
   Caulobacteraceae       0.00      0.00      0.00         3
     Comamonadaceae       0.00      0.00      0.00        40
      Cytophagaceae       0.00      0.00      0.00         1
        Erwiniaceae       0.73      0.47      0.57       368
Methylobacteriaceae       0.10      0.02      0.04       131
  Microbacteriaceae       0.00      0.00      0.00       246
     Micrococcaceae       0.00      0.00      0.00        15
      Moraxellaceae       0.00      0.00      0.00         4
       Nocardiaceae       0.00      0.00      0.00        51
   Pseudomonadaceae       0.48      0.97      0.64       574
       Rhizobiaceae       0.00      0.00      0.00       118
  Sphingomonadaceae       0.60      0.81      0.69       677
       Yersiniaceae       0.00      0.00      0.00       103

          micro avg       0.54      0.54      0.54      2365
          macro avg       0.12      0.14      0.12      2365
       weighted avg       0.41      0.54      0.44      2365


Warning: Found 28 unknown host Host_order labels in test data:
Unknown labels: {'Eubacteriales', 'Oscillatoriales', 'Lysobacterales', 'Pseudonocardiales', 'Methylococcales', 'Propionibacteriales', 'Candidatus Saccharimonadales', 'Vibrionales', 'Nitrospirales', 'Lactobacillales', 'Oceanospirillales', 'Bifidobacteriales', 'Kitasatosporales', 'Synechococcales', 'Lachnospirales', 'Deinococcales', 'Bacteroidales', 'Sphingobacteriales', 'Fusobacteriales', 'Coriobacteriales', 'Flavobacteriales', 'Nostocales', 'Aggregatilineales', 'Legionellales', 'Geodermatophilales', 'Selenomonadales', 'Actinomycetales', 'Cellvibrionales'}
These samples will be excluded from evaluation

Host Host_order Accuracy: 0.5024
Number of test samples: 3083
Number of classes in test: 12

Classification Report:
                  precision    recall  f1-score   support

      Bacillales       0.00      0.00      0.00         4
 Burkholderiales       0.50      0.01      0.03        78
 Caulobacterales       0.00      0.00      0.00         3
    Cytophagales       0.00      0.00      0.00       301
Enterobacterales       0.94      0.58      0.72       688
Hyphomicrobiales       0.05      0.01      0.02       300
   Micrococcales       0.00      0.00      0.00       273
    Moraxellales       0.00      0.00      0.00         4
 Mycobacteriales       0.00      0.00      0.00       177
 Pseudomonadales       0.39      0.95      0.56       574
 Rhodobacterales       0.00      0.00      0.00         1
Sphingomonadales       0.50      0.88      0.64       680

        accuracy                           0.50      3083
       macro avg       0.20      0.20      0.16      3083
    weighted avg       0.41      0.50      0.41      3083


Warning: Found 12 unknown host Host_class labels in test data:
Unknown labels: {'Cyanophyceae', 'Clostridia', 'Deinococci', 'Negativicutes', 'Sphingobacteriia', 'Fusobacteriia', 'Anaerolineae', 'Bacteroidia', 'Flavobacteriia', 'Nitrospiria', 'Coriobacteriia', 'Candidatus Saccharimonadia'}
These samples will be excluded from evaluation

Host Host_class Accuracy: 0.6276
Number of test samples: 3201
Number of classes in test: 6

Classification Report:
                     precision    recall  f1-score   support

      Actinomycetes       0.00      0.00      0.00       536
Alphaproteobacteria       0.63      0.76      0.69       984
            Bacilli       0.00      0.00      0.00        15
 Betaproteobacteria       0.00      0.00      0.00        78
         Cytophagia       0.00      0.00      0.00       301
Gammaproteobacteria       0.62      0.98      0.76      1287

           accuracy                           0.63      3201
          macro avg       0.21      0.29      0.24      3201
       weighted avg       0.45      0.63      0.52      3201


Warning: Found 6 unknown host Host_phylum labels in test data:
Unknown labels: {'Nitrospirota', 'Fusobacteriota', 'Cyanobacteriota', 'Deinococcota', 'Chloroflexota', 'Candidatus Saccharibacteria'}
These samples will be excluded from evaluation

Host Host_phylum Accuracy: 0.7221
Number of test samples: 3253
Number of classes in test: 4

Classification Report:
                precision    recall  f1-score   support

Actinomycetota       0.00      0.00      0.00       543
     Bacillota       0.00      0.00      0.00        27
  Bacteroidota       0.00      0.00      0.00       334
Pseudomonadota       0.72      1.00      0.84      2349

      accuracy                           0.72      3253
     macro avg       0.18      0.25      0.21      3253
  weighted avg       0.52      0.72      0.61      3253
