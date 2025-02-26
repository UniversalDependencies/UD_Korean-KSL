# Summary
UD_Korean-KSL is a dependency treebank of second-language (L2) Korean.

# Introduction
- Morpheme annotations (XPOS) are based on the Sejong tag set and have been manually annotated.
- Universal part of speech (UPOS) tags were automatically added using Stanza, which was trained on the [UD_Korean-GSD](https://github.com/UniversalDependencies/UD_Korean-GSD) dataset and then partially corrected. We plan to update these tags soon following manual inspection.
- The dependency structures adhere to the Universal Dependencies (v2.0) framework. They were initially generated automatically using Stanza and then manually corrected 
- The current version contains a total of 12,977 sentences: 10,323 in the train set, 1,311 in the test set, and 1,343 in the dev set.
- The treebank includes two distinct datasets:
  - Kyung Hee Korean Learner Corpus (KH): Sentences are identified by IDs beginning with `KH` and include classroom proficiency levels (A1 to C2) as a proxy for learner ability.
  - [KoLLA](https://cl.indiana.edu/~kolla/): Sentences have IDs starting with `KL` and are categorized into proficiency groups: fb (Foreign Beginners), fi (Foreign Intermediates), and hb (Heritage Beginners).

# Acknowledgements

- We acknowledge the original data contributors: the Kyung Hee dataset (credit to Jungyeul Park and Jung Hee Lee; note that this dataset is no longer maintained and its sentences are no longer used for further annotation) and the KoLLA dataset (credit to Markus Dickinson, Ross Israel, and Sun-Hee Lee).
- We acknowledge our annotators: Hee-June Koh, Chanyoung Lee, and Youkyung Sung.

# References 
- For additional details, please refer to the [supplemnentary repo](https://github.com/NLPxL2Korean/UD-KSL) for more information on recent papers, annotation guidelines, and fine-tuned models for L2-Korean.

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