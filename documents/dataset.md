### new millard dataset

seq length:
count     33166.000000
mean      60853.816348
std       55336.412598
min        1761.000000
25%       34593.000000
50%       45404.000000
75%       68389.000000
max      735411.000000

columns:
'Accession', 'Description', 'Classification', 'Genome Length (bp)','Jumbophage', 'molGC (%)', 'Molecule', 'Modification Date', 'Number CDS', 'Positive Strand (%)', 'Negative Strand (%)',  'Coding Capacity (%)', 'Low Coding Capacity Warning', 'tRNAs', 'Host', 'Lowest Taxa', 
'Genus', 'Sub-family', 'Family', 'Order', 'Class', 'Phylum', 'Kingdom', 'Realm', 
'Baltimore Group', 'Genbank Division', 'Isolation Host (beware inconsistent and nonsense values)',
'Host_domain', 'Host_phylum', 'Host_class', 'Host_order', 'Host_family', 'Host_genus'

metadata:

Genus Unclassified: 0.31174430875923415
Sub-family Unclassified: 0.6947384290667873
Family Unclassified: 0.5673149404492688
Order Unclassified: 0.8221317654153475
Class Unclassified: 0.06941052314186642
Phylum Unclassified: 0.06941052314186642
Kingdom Unclassified: 0.06941052314186642
Realm Unclassified: 0.06941052314186642

Host Unspecified: 0.092054877129504
Host_genus is nan: 0.12069953263983114
Host_family is nan: 0.12045831448816524
Host_order is nan: 0.12015679179858284
Host_class is nan: 0.1201266395296246
Host_phylum is nan: 0.12003618272274989
Host_domain is nan: 1.0

number of genera: 1427
number of sub-families: 111
number of families: 88
number of orders: 18
number of classes: 11
number of phylums: 10
number of kingdoms: 9
number of realms: 6

number of hosts: 337
number of host genera: 316
number of host families: 147
number of host orders: 84
number of host classes: 39
number of host phylums: 24
number of host domains: 1

### new matrix dataset
viral sequences assembled from metagenomes; sequences are from viruses found in the phyllosphere (the surface of plant leaves)
no ground-truth host

seq length
count      8399.000000
mean      24608.987499
std       20124.994540
min        4441.000000
25%       12782.000000
50%       17745.000000
75%       30802.500000
max      354857.000000

columns:
'vOTU', 'length', 'geNomad_viral_conservative', 'checkv_quality', 'iphop_host_confidence_score', 
'iphop_host_phylum', 'iphop_host_class', 'iphop_host_order', 'iphop_host_family', 'iphop_host_genus', 
'PhaGCN_viral_phylum', 'PhaGCN_viral_class', 'PhaGCN_viral_order', 'PhaGCN_viral_family', 
'taxmyphage_viral_Kingdom', 'taxmyphage_viral_Phylum', 'taxmyphage_viral_Class', 'taxmyphage_viral_Order', 'taxmyphage_viral_Family', 'taxmyphage_viral_Subfamily', 'taxmyphage_viral_Genus', 'taxmyphage_viral_Species'

column	description
length	Contig Length
geNomad_viral_conservative	Viral confidence by geNomad (conservative mode)
checkv_quality	Genome quality estimation from CheckV
iphop_host_confidence_score	Confidence score for predicted host taxonomy (iPHoP)
iphop_host_phylum	Predicted host phylum (iPHoP)
iphop_host_class	Predicted host class (iPHoP)
iphop_host_order	Predicted host order (iPHoP)
iphop_host_family	Predicted host family (iPHoP)
iphop_host_genus	Predicted host genus (iPHoP)
PhaGCN_viral_phylum	Predicted viral phylum from PhaGCN model
PhaGCN_viral_class	Predicted viral class from PhaGCN model
PhaGCN_viral_order	Predicted viral order from PhaGCN model
PhaGCN_viral_family	Predicted viral family from PhaGCN model
taxmyphage_viral_Kingdom	Predicted viral kingdom from taxmyphage
taxmyphage_viral_Phylum	Predicted viral phylum from taxmyphage
taxmyphage_viral_Class	Predicted viral class from taxmyphage
taxmyphage_viral_Order	Predicted viral order from taxmyphage
taxmyphage_viral_Family	Predicted viral family from taxmyphage
taxmyphage_viral_Subfamily	Predicted viral subfamily from taxmyphage
taxmyphage_viral_Genus	Predicted viral genus from taxmyphage
taxmyphage_viral_Species	Predicted viral species from taxmyphage

Species is nan (taxmyphage): 0.9978568877247291
Genus is nan (taxmyphage): 0.9978568877247291
Sub-family is nan (taxmyphage): 0.9978568877247291
Family is nan (taxmyphage): 0.9978568877247291
Order is nan (taxmyphage): 0.9978568877247291
Class is nan (taxmyphage): 0.9978568877247291
Phylum is nan (taxmyphage): 0.9978568877247291
Kingdom is nan (taxmyphage): 0.9978568877247291
Family is nan (PhaGCN): 0.41338254554113585
Order is nan (PhaGCN): 1.0
Class is nan (PhaGCN): 0.41338254554113585
Phyllum is nan (PhaGCN): 0.41338254554113585
Host genus is nan (iPHoP): 0.6085248243838552
Host family is nan (iPHoP): 0.6091201333492082
Host order is nan (iPHoP): 0.6085248243838552
Host class is nan (iPHoP): 0.6085248243838552
Host phyllum is nan (iPHoP): 0.6085248243838552

Taxmyphage's predictions can be treated as "ground truth"; good at classifying sequences that are already known — ones that exist in current databases
PhaGCN works better for lower-resolution taxonomy, especially at the family level; useful when working with novel sequences

### strain dataset
Comes from bacterial isolates — ground-truth host available

seq lenth
count      3239.000000
mean      31292.787589
std       18712.219444
min       10002.000000
25%       15445.000000
50%       27973.000000
75%       42848.000000
max      138160.000000

Index(['contig_id', 'length', 'geNomad_viral_conservative', 'checkv_quality',
       'iphop_host_confidence_score', 'iphop_host_phylum', 'iphop_host_class',
       'iphop_host_order', 'iphop_host_family', 'iphop_host_genus',
       'PhaGCN_viral_phylum', 'PhaGCN_viral_class', 'PhaGCN_viral_order',
       'PhaGCN_viral_family', 'taxmyphage_viral_Kingdom',
       'taxmyphage_viral_Phylum', 'taxmyphage_viral_Class',
       'taxmyphage_viral_Order', 'taxmyphage_viral_Family',
       'taxmyphage_viral_Subfamily', 'taxmyphage_viral_Genus',
       'taxmyphage_viral_Species', 'ground_truth_host_phylum',
       'ground_truth_host_class', 'ground_truth_host_order',
       'ground_truth_host_family', 'ground_truth_host_genus',
       'ground_truth_host_species'],
      dtype='object')

column	description
length	Contig Length
geNomad_viral_conservative	Viral confidence by geNomad (conservative mode)
checkv_quality	Genome quality estimation from CheckV
iphop_host_confidence_score	Confidence score for predicted host taxonomy (iPHoP)
iphop_host_phylum	Predicted host phylum (iPHoP)
iphop_host_class	Predicted host class (iPHoP)
iphop_host_order	Predicted host order (iPHoP)
iphop_host_family	Predicted host family (iPHoP)
iphop_host_genus	Predicted host genus (iPHoP)
PhaGCN_viral_phylum	Predicted viral phylum from PhaGCN model
PhaGCN_viral_class	Predicted viral class from PhaGCN model
PhaGCN_viral_order	Predicted viral order from PhaGCN model
PhaGCN_viral_family	Predicted viral family from PhaGCN model
taxmyphage_viral_Kingdom	Predicted viral kingdom from taxmyphage
taxmyphage_viral_Phylum	Predicted viral phylum from taxmyphage
taxmyphage_viral_Class	Predicted viral class from taxmyphage
taxmyphage_viral_Order	Predicted viral order from taxmyphage
taxmyphage_viral_Family	Predicted viral family from taxmyphage
taxmyphage_viral_Subfamily	Predicted viral subfamily from taxmyphage
taxmyphage_viral_Genus	Predicted viral genus from taxmyphage
taxmyphage_viral_Species	Predicted viral species from taxmyphage
ground_truth_host_phylum	Ground truth host phylum
ground_truth_host_class	Ground truth host class
ground_truth_host_order	Ground truth host order
ground_truth_host_family	Ground truth host family
ground_truth_host_genus	Ground truth host genus
ground_truth_host_species	Ground truth host species

iphop_host_genus is nan: 0.07286199444272924
iphop_host_family is nan: 0.07286199444272924
iphop_host_order is nan: 0.07286199444272924
iphop_host_class is nan: 0.07286199444272924
iphop_host_phylum is nan: 0.07286199444272924
ground_truth_host_species is nan: 0.0
ground_truth_host_genus is nan: 0.0
ground_truth_host_family is nan: 0.0
ground_truth_host_order is nan: 0.0
ground_truth_host_class is nan: 0.0
ground_truth_host_phylum is nan: 0.0
PhaGCN_viral_family is nan: 0.32201296696511267
PhaGCN_viral_order is nan: 1.0
PhaGCN_viral_class is nan: 0.32201296696511267
PhaGCN_viral_phylum is nan: 0.32201296696511267
taxmyphage_viral_Species is nan: 1.0
taxmyphage_viral_Genus is nan: 1.0
taxmyphage_viral_Subfamily is nan: 1.0
taxmyphage_viral_Family is nan: 1.0
taxmyphage_viral_Order is nan: 1.0
taxmyphage_viral_Class is nan: 1.0
taxmyphage_viral_Phylum is nan: 1.0
taxmyphage_viral_Kingdom is nan: 1.0