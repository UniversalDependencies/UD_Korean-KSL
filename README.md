# Summary

UD_Korean-KSL is a dependency treebank of L2 Korean, featuring morpheme and Universal Dependency manual annotations for six hundred randomly sampled texts from the Kyung Hee Korean Learner Corpus (which is no longer available).

# Introduction

- Language-specific morpheme tags (XPOS) are based on the Sejong tag set and were manually annotated.
- Dependency annotations adhere to the Universal Dependencies (version 2.0) framework and were manually annotated (initially tagged automatically by Stanza, then corrected).
- Universal part of speech (UPOS) tags were automatically added using Stanza, which was trained on the [UD_Korean-GSD](https://github.com/UniversalDependencies/UD_Korean-GSD) dataset and then partially corrected. We plan to update these tags soon following manual inspection.
- The current version contains a total of 7,530 sentences: 5,627 in the train set, 1,150 in the test set, and 753 in the dev set. The data also includes details on classroom proficiency levels (ranging from A1 to C2, serving as a proxy for learner proficiency). We plan to update the proficiency ratings provided by trained human raters.

## References

- Sung, H., & Shin, G-H. (2023). [Towards L2-friendly pipelines for learner corpora: A case of written production by L2-Korean learners](https://aclanthology.org/2023.bea-1.6/). In *Proceedings of the 18th Workshop on Innovative Use of NLP for Building Educational Applications (BEA 2023)*, 72-82, Association for Computational Linguistics. 
- Sung, H., & Shin, G-H. (2024). [Constructing a Dependency Treebank for Second Language Learners of Korean](https://aclanthology.org/2024.lrec-main.332/). In *Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)* (pp. 3747-3758).

# Changelog
* 2024-11-11 v2.15
  * Initial release in Universal Dependencies
  * Minor update on the README
* 2024-10-16
  * Updated the source data information
* 2024-05-15 v2.14
  * Release in Universal Dependencies (dev-repo)

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.14
License: CC BY-SA 4.0
Includes text: yes
Genre: learner-essays
Lemmas: manual native
UPOS: converted with corrections
XPOS: manual native
Features: manual native
Relations: converted with corrections
Contributors: Sung, Hakyung; Shin, Gyu-Ho
Contributing: here
Contact: hsung@uoregon.edu
===============================================================================
</pre>
