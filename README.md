# Summary

UD_Korean-KSL is a dependency treebank of second-language (L2) Korean.

# Introduction

The annotated sentences are sourced from three datasets: (1) the Kyung Hee dataset, with sentence IDs starting with `KH` and annotated with classroom proficiency levels (A1–C2); (2) the KoLLA dataset, with sentence IDs starting with `KL` and grouped as fb (foreign beginners), fi (foreign intermediates), and hb (heritage beginners); (3) argumentative essays, with sentence IDs starting with `ARG` and grouped by first language: CHN (Chinese), CZH (Czech), ENG (English), and JPN (Japanese).


# Acknowledgements

We acknowledge the original data contributors: (1) the Kyung Hee dataset (credit to Jungyeul Park and Jung Hee Lee; note that its sentences are not used for further annotation); (2) the KoLLA dataset (credit to Markus Dickinson, Ross Israel, and Sun-Hee Lee); and (3) the argumentative essays (credit to Boo Kyung Jung and Jeong Eun Shin).  

# References 

Please refer to the [supplementary repo](https://github.com/NLPxL2Korean/UD-KSL) for more information on recent papers, annotation guidelines, and fine-tuned models for L2-Korean.

# Changelog

* 2026-04-23
  * Fixed validation issues:
    * L3 Warning pron-det-without-prontype: Added missing `PronType` features to pronominal and determiner forms by assigning `PronType=Prs` to `PRON` (e.g., 나, 저, 우리), and `PronType=Dem` or `PronType=Int` to `DET` (e.g., 그, 이, 무엇), and updated the Korean language-specific validator settings to permit these `PronType × UPOS` combinations.
    * L3 Syntax obl-should-be-nmod: Corrected case-marked noun phrases attached to nominal heads by changing the dependency label from `obl` to `nmod`.
  
* 2025-10-17
  * Current version: 12,721 train, 1,311 dev, 1,643 test — total 15,675 sentences.
  * Fixed validation issues:
    * L3 Syntax too-many-objects: Reanalyzed *light-verb constructions* (e.g., `이야기/계획/연습/추천/선택/치료/생각/극복/시작/경험 하다`) by changing the noun dependency relation from `obj` to `compound:lvc`.
    * L3 Warning obl-should-be-nmod: Corrected case-marked noun phrases functioning as nominal modifiers by changing the label from `obl` to `nmod`.
    * Length mismatches: Resolved tokenization inconsistencies between surface forms and corresponding morphological analyses.
    * Comment=Case/Spelling/SpacingError (10th column): Temporarily retained learner error annotations in the MISC column; these entries will be reviewed and standardized in the next annotation phase.
* 2025-07-03 (UD-KSL v1.3)  
  * Added 2,998 new sentences  
  * Introduced a `semi-automated framework` that identifies morphosyntactic constructions from XPOS sequences and aligns them with corresponding UPOS categories (db [here](https://github.com/NLPxL2Korean/UD-KSL/blob/main/dataset/xpos_upos_mapping_db_v1.0.txt))
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
Parallel: no
Genre: learner-essays
Lemmas: manual native
UPOS: converted with corrections
XPOS: manual native
Features: converted from manual
Relations: manual native
Contributors: Sung, Hakyung; Shin, Gyu-Ho
Contributing: here
Contact: hksung001@gmail.com; Shin, ghshin@uic.edu
===============================================================================
</pre>
