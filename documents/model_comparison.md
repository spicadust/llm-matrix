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


Warning: Found 41 unknown host Host_genus labels in test data:
Unknown labels: {' Williamsia', ' Spirosoma', ' Microbacterium', ' Variovorax', ' Methylobacterium', ' Bacillus', ' Pantoea', ' Ewingella', ' Rhodococcus', ' Frondihabitans', ' Paenarthrobacter', ' Acinetobacter', ' Rahnella', ' Micrococcus', ' Rosenbergiella', ' Paracoccus', ' Frigoribacterium', ' Pseudoclavibacter', ' Dermacoccus', ' Peribacillus', ' Sphingomonas', ' Belnapia', ' Erwinia', ' Oceanobacillus', ' Pseudomonas', ' Priestia', ' Pararhizobium', ' Aureimonas', ' Rathayibacter', ' Arthrobacter', ' Serratia', ' Ralstonia', ' Brevundimonas', ' Pseudarthrobacter', ' Agromyces', ' Paraburkholderia', ' Methylopila', ' Clavibacter', ' Cytobacillus', ' Staphylococcus', ' Curtobacterium'}
These samples will be excluded from evaluation

No valid test samples for host Host_genus

Warning: Found 21 unknown host Host_family labels in test data:
Unknown labels: {' Bacillaceae', ' Nocardiaceae', ' Pseudomonadaceae', ' Microbacteriaceae', ' Moraxellaceae', ' Burkholderiaceae', ' Methylobacteriaceae', ' Cytophagaceae', ' Micrococcaceae', ' Dermacoccaceae', ' Aurantimonadaceae', ' Acetobacteraceae', ' Paracoccaceae', ' Methylopilaceae', ' Erwiniaceae', ' Caulobacteraceae', ' Yersiniaceae', ' Comamonadaceae', ' Staphylococcaceae', ' Sphingomonadaceae', ' Rhizobiaceae'}
These samples will be excluded from evaluation

No valid test samples for host Host_family

Warning: Found 13 unknown host Host_order labels in test data:
Unknown labels: {' Hyphomicrobiales', ' Pseudomonadales', ' Micrococcales', ' Rhodobacterales', ' Sphingomonadales', ' Rhodospirillales', ' Bacillales', ' Enterobacterales', ' Burkholderiales', ' Cytophagales', ' Mycobacteriales', ' Caulobacterales', ' Moraxellales'}
These samples will be excluded from evaluation

No valid test samples for host Host_order

Warning: Found 6 unknown host Host_class labels in test data:
Unknown labels: {' Gammaproteobacteria', ' Betaproteobacteria', ' Alphaproteobacteria', ' Cytophagia', ' Actinomycetes', ' Bacilli'}
These samples will be excluded from evaluation

No valid test samples for host Host_class

Warning: Found 4 unknown host Host_phylum labels in test data:
Unknown labels: {' Actinomycetota', ' Bacteroidota', ' Bacillota', ' Pseudomonadota'}
These samples will be excluded from evaluation

No valid test samples for host Host_phylum
