# FLC probe search

---
title: "FLC probes in Brassica validation"
author: Chung-Wen Lin
date: 2017-01-10
---

A. According to the annotation file of Brassica chip "022520\_bna1\_1468306608983", there are **4** probes which match the keyword "FLC":

    |probe|
    |-----|
    |A\_46\_P354020|
    |A\_46\_P009006|
    |A\_46\_P009001|
    |A\_46\_P009856|

B. According to the annotation file provided by Fu, there are **5** probes which match the keyword "AT5G10104":

    |probe|
    |-----|
    |A\_46\_P370555|
    |A\_46\_P324965|
    |A\_46\_P009856|
    |A\_46\_P009006|

C. To further validate these probes, the following FLC sequences are used as query and/or target (Full cDNA / genomic sequence is used here.):

    |Symbol|Locus|Note|With complete CDS|
    |------|-----|----|-----------------|
    |HT-FLC1|CNE-FLC1|longest peptide: 119 aa| Yes |
    |HS-FLC1|CNL-FLC1|longest peptide: 119 aa| Yes |
    |HT-FLC2|CNE-FLC2|unable to identify peptide length > 100 aa| N/A |
    |HS-FLC2|CNL-FLC2|unable to identify peptide length > 100 aa| N/A |
    |HT-FLC4|CNE-FLC4|unable to identify peptide length > 100 aa| N/A |
    |HS-FLC4|CNL-FLC4|unable to identify peptide length > 100 aa| N/A |
    |AtFLC|AT5G10140|longest peptide: 196 aa| Yes |
    |BnFLC3|AY036890|longest peptide: 213 aa| partial |
    |BnFLC4|AY036891|longest peptide: 197 aa| Yes |
    |BnFLC1|AY036888|longest peptide: 198 aa| Yes |
    |BoFLC1|AY115674|longest peptide: aa| partial |BoFLC3|AY115673|longest peptide: 135 aa| Yes |BoFLC4|AY306122|longest peptide: 198 aa| Yes |
    |BoFLC5|AY115672|longest peptide: aa| partial|

D. Alignment result
![Brassica chip FLC probes](http://140.116.25.64/~lincw/images/Brassica%20chip%20FLC%20%20probes%20alignment.png)