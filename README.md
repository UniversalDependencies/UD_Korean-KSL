# Summary

UD_Korean-KSL is a dependency treebank of L2 Korean, featuring morpheme and Universal Dependency manual annotations for six hundred randomly sampled texts from the [Kyung Hee Korean Learner Corpus](https://github.com/jungyeul/korean-learner-corpus). The current version of the dataset only focuses on written second language Korean. Two related projects are also available: (1) [KLM-corpus](https://github.com/NLPxL2Korean/KLM-corpus) and (2) [homepage for this project](https://github.com/NLPxL2Korean/L2KW-corpus).

# Introduction

- Language-specific morpheme tags (XPOS) were based on the [Sejong tag set](https://github.com/NLPxL2Korean/L2KW-corpus) aand were manually annotated from scratch by three native Korean-speaking annotators. Detailed processes for data construction are outlined in this [paper](https://aclanthology.org/2023.bea-1.6/).

- Dependency annotations adhere to the Universal Dependencies (version 2.0) framework and were manually annotated (initially tagged automatically by Stanza, then corrected by at least three Korean annotators). Detailed tagging guidelines and annotation processes are discussed in the Sung & Shin (forthcoming) paper (which will be updated soon).

- Universal part of speech (UPOS) tags were automatically added using Stanza.

# Acknowledgments

The authors gratefully acknowledge Youkyung Sung for her contributions to the manual annotations and discussions that enhanced the tokenizing and POS tagging guidelines for the L2 Korean dataset.

## References

* Sung, H., & Shin, G. H. (2023). [Towards L2-friendly pipelines for learner corpora: A case of written production by L2-Korean learners](https://aclanthology.org/2023.bea-1.6/). In *Proceedings of the 18th Workshop on Innovative Use of NLP for Building Educational Applications (BEA 2023)*, 72-82, Association for Computational Linguistics. 

* Sung, H., & Shin, G. H. (forthcoming). Constructing a Dependency Treebank for Second Language Learners of Korean. In *LREC-COLING*.

# Changelog

* 2024-05-15 v2.14
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.14
License: CC BY-SA 4.0
Includes text: yes
Genre: learner-essays
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Sung, Hakyung; Shin, Gyu-Ho
Contributing: here
Contact: hsung@uoregon.edu
===============================================================================
</pre>
