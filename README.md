# Summary

UD_Korean-KSL is a dependency treebank of second-language (L2) Korean.

# Introduction

The treebank contains 12,977 sentences—10,323 in the training set, 1,311 in the dev set, and 1,343 in the test set. These sentences are sourced from two datasets: (1) the Kyung Hee dataset, with sentence IDs starting with “KH” and annotated with classroom proficiency levels (A1–C2); and (2) the KoLLA dataset, with sentence IDs starting with “KL” and grouped as fb (foreign beginners), fi (foreign intermediates), and hb (heritage beginners).

# Acknowledgements

We acknowledge the original data contributors: the Kyung Hee dataset (credit to Jungyeul Park and Jung Hee Lee; note that this dataset is no longer maintained and its sentences are no longer used for further annotation) and the KoLLA dataset (credit to Markus Dickinson, Ross Israel, and Sun-Hee Lee). We also acknowledge our annotators: Hee-June Koh, Chanyoung Lee, and Youkyung Sung.

# References 

Please refer to the [supplemnentary repo](https://github.com/NLPxL2Korean/UD-KSL) for more information on recent papers, annotation guidelines, and fine-tuned models for L2-Korean.

# Changelog

* 2025-02-25
  * Added 5,447 new sentences
  * Introduced the `Typo=Yes` feature to indicate erroneous or unexpected word forms
* 2024-11-11 v2.15
  * Initial release in Universal Dependencies
  * Minor update on the README
* 2024-10-16
  * Updated the source data information
* 2024-05-15 v2.14
  * Release in Universal Dependencies (dev-repo)

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.15
License: CC BY-SA 4.0
Includes text: yes
Genre: learner-essays
Lemmas: manual native
UPOS: converted with corrections
XPOS: manual native
Features: converted from manual
Relations: manual native
Contributors: Sung, Hakyung; Shin, Gyu-Ho
Contributing: here
Contact: hsung@uoregon.edu
===============================================================================
</pre>
