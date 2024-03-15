# DiscoGeM
 
This repository contains the DiscoGeM corpus: A Crowdsourced Corpus of Genre-Mixed Inter-Sentential Implicit Discourse Relations annotated in PDTB3-style.

 ## DiscoGeM 1.0
 
DiscoGeM 1.0 is a crowdsourced corpus of 6,505 implicit discourse relations from different genres in English. It contains data from political speech (Europarl), literature, and encyclopedic (Wikipedia) texts. It has now been updated with annotations of an additional set of 300 implicit relations from the Penn Discourse Treebank (data stemming from newspaper text), to allow for a comparison between the methodologies.

Each instance in DiscoGeM was annotated by 10 crowd workers, using a discourse connective insertion paradigm (see Yung et al., 2019; Scholman et al., 2022). In addition to the annotated dataset, we also make available the dataset with all annotator-level insertions and annotator quality scores.

A subset of the data was also annotated using a Question-Answer annotation paradigm (see Pyatkin et al., 2023). These annotations can be found in the folder QADiscourse_annotations.

 ## DiscoGeM 2.0

 DiscoGeM 2.0 is a crowdsourced, parallel corpus of 12,834 implicit discourse relations, with English, German, French and Czech data.  It contains data from Europarl and literature. The English annotation comes from DiscoGeM 1.0 and the German, French and Czech data comes from the translation of the English data, or the originals of the translated English data.

 ***Europarl***
Original / data lang  | EN  | DE   | FR  | CS 
----------------------|-----|------|-----|----
English               | 418 | 417  | 414 | -
German                | 701 | 701  | -   | -
French                | 739 | -    | 727 | -
Czezh                 | 700 | -    |  -  | 697
**Subtotal**        | **2558** | **1118**| **1141**| **697**

 ***Literature***
Original / data lang  | EN  | DE   | FR  | CS 
----------------------|-----|------|-----|----
English               | 800 | 787  | 758 | 777
German                | 800 | 683  | -   | -
French                | 780 | -    | 729 | -
Czezh                 | 680 | -    |  -  | 526
**Subtotal**        | **3060** | **1470**| **1487**| **1303**

Each instance was annotated by 10 crowd workers who are native speakers of the language, using an approach adapted from the discourse connective insertion task used in DiscoGeM 1.0 (see Yung et al, 2024). The data includes the crowdsourced label distributions, aggregated labels (by majority voting, Dawid-Skene, MACE, etc), as well as annotator-level information.

 
 ## Reference
 If you use this resource, please consider citing:
 
        @inproceedings{scholman2022DiscoGeM,
           title = "DiscoGeM: A Crowdsourced Corpus of Genre-Mixed Implicit Discourse Relations",
           author = "Scholman, Merel C. J.  and
           Dong, Tianai and
           Yung, Frances and
           Demberg, Vera",
           booktitle = "Proceedings of the Thirteenth International Conference on Language Resources and Evaluation ({LREC}'22)",
           month = June,
           year = "2022",
           address = "Marseille, France",
           publisher = "European Language Resources Association (ELRA)"
       }

       @inproceedings{yung2024DiscoGeM,
           title = "DiscoGeM 2.0: A Parallel Corpus of English, German, French and Czech implicit discourse relations",
           author = "Yung, Frances  and
           Scholman, Merel C. J. and
           Zikanova, Sarka and
           Demberg, Vera",
           booktitle = "Proceedings of the Joint International Conference on Computational Linguistics, Language Resources and Evaluation ({LREC-COLING}'24)",
           month = May,
           year = "2024",
           address = "Turin, Italy",
           publisher = "European Language Resources Association (ELRA) and International Committee on Computational Linguistics (ICCL)"
       }


## Related work

<a id="1">[1]</a> 
Pyatkin, V., Yung, F., Scholman, M.C.J., Dagan, I., Tsarfaty, R., & Demberg, V. (2023). 
Design Choices for Crowdsourcing Implicit Discourse Relations: Revealing the Biases introduced by Task Design. 
TACL.

<a id="1">[2]</a> 
Scholman, M.C.J., Pyatkin, V., Yung, F., Dagan, I., Tsarfaty, R., & Demberg, V. (2022).
Design Choices in Crowdsourcing Discourse Relation Annotations: The Effect of Worker Selection and Training. 
Proceedings of the 13th International Conference on Language Resources and Evaluation (LREC 22), Marseille, France.

<a id="1">[3]</a> 
Yung, F., Demberg, V., & Scholman, M.C.J. (2019). 
Crowdsourcing discourse relation annotations by a two-step connective insertion task. 
Proceedings of the 13th Linguistic Annotation Workshop, Florence, Italy.
