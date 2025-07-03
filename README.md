# Summary

UD_Korean-KSL is a dependency treebank of second-language (L2) Korean.

# Introduction

The annotated sentences are sourced from three datasets: (1) the Kyung Hee dataset, with sentence IDs starting with `KH` and annotated with classroom proficiency levels (A1–C2); (2) the KoLLA dataset, with sentence IDs starting with `KL` and grouped as fb (foreign beginners), fi (foreign intermediates), and hb (heritage beginners); (3) argumentative essays, with sentence IDs starting with `ARG` and grouped by first language: CHN (Chinese), CZH (Czech), and ENG (English).


# Acknowledgements

We acknowledge the original data contributors: (1) the Kyung Hee dataset (credit to Jungyeul Park and Jung Hee Lee; note that its sentences are not used for further annotation); (2) the KoLLA dataset (credit to Markus Dickinson, Ross Israel, and Sun-Hee Lee); and (3) the argumentative essays (credit to Boo Kyung Jung).  

# References 

Please refer to the [supplementary repo](https://github.com/NLPxL2Korean/UD-KSL) for more information on recent papers, annotation guidelines, and fine-tuned models for L2-Korean.

# Changelog


* 2025-07-03 (UD-KSL v1.3)  
  * Added 2,998 new sentences  
  * Introduced a `semi-automated framework` that identifies morphosyntactic constructions from XPOS sequences and aligns them with corresponding UPOS categories (See `data/xpos_upos_mapping_db_v1.0.txt`)
* 2025-02-25 (UD-KSL v1.2)  
  * Added 5,447 new sentences  
  * Introduced the `Typo=Yes` feature to indicate erroneous or unexpected word forms  
  * Revised annotation guidelines to better align with the UD framework  
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
