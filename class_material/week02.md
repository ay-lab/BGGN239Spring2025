---
layout: page
title: Week 2 - Ferhat Ay
menu: false
description: >
  **Key Point:** To fully participate in the hands-on sections of this course you will need to refresh your R and UNIX skills as well as have access to specific software on your own laptop that you bring to each class.
---

> ### On this page:
- Class 0: [Finishing up the SLE exercise](#0).
- Class 1. [ClusterProfiler GO term enrichment analysis](#1).
- Class 2: [ClusterProfiler gene set enrichment analysis](#2).
- Class 3: [RNA-Seq analysis mini-project](#3).
- Optional (Advanced): [WGCNA - Weighted gene co-expression network analysis](#4).
<br/>

<a name="0"></a>
## Class 0: Finishing up the SLE exercise 

**Topics:**  
- Finishing up the DESeq portion of the SLE exercise
- Getting gene sets and saving them with all the related information to continue Week 2 exercises

**Supporting material:**  
- Lab from Week 1: [DESeq2 analysis mini-project]({{ site.baseurl }}/class_material/class2_lab.html){:.no-push-state}{:target="_blank"}.  
- Illustrations of how dplyr functions work: [By Allison Horst](https://allisonhorst.com/r-packages-functions){:.no-push-state}, 



--- 
<a name="1"></a>
### Class 1. Transcriptomics and the analysis of RNA-Seq data

**Topics:** 
Analysis of RNA-Seq data with R, Differential expression tests, RNA-Seq statistics, Counts and FPKMs, Normalizing for sequencing depth, DESeq2 analysis. Gene finding and functional annotation from high throughput sequencing data, Functional databases KEGG, InterPro, GO ontologies and functional enrichment.  


**Goals:**  
- Given an RNA-Seq dataset, find the set of significantly differentially expressed genes and their annotations.  
- Gain competency with data import, processing and analysis with DESeq2 and other bioconductor packages.  
- Understand the structure of count data and metadata required for running analysis.  
- Be able to extract, explore, visualize and export results.  
- Perform a GO analysis to identify the pathways relevant to a set of genes (e.g. identified by transcriptomic study or a proteomic experiment). Use both Bioconductor packages and online tools to interpret gene lists and annotate potential gene functions.

**Videos:**
- 1.1 - [Differential expression analysis of RNA-Seq data](https://youtu.be/JxMpV6QUxS0){:.no-push-state}{:target="_blank"},  
- 1.2 - [Differential expression tests and pathway analysis](https://youtu.be/Wjxh8Cw1n1s){:.no-push-state}{:target="_blank"},    
- 1.3 - [Installing Bioconductor and DESeq2](http://youtu.be/aekKXg0U1Rg){:.no-push-state}{:target="_blank"},    
- 1.4 - [Principal component analysis (PCA) Pt.1](http://youtu.be/Olm0gW6OXIg){:.no-push-state}{:target="_blank"},   


**Supporting material:**
- Slides: [Large PDF]({{ site.baseurl }}/class_material/class01_slides.pdf){:.no-push-state}{:target="_blank"},  
- Lab: [**Hands-on section worksheet**  ]({{ site.baseurl }}/class_material/class1_lab.html){:.no-push-state}{:target="_blank"},  
- Detailed [Bioconductor setup](https://bioboot.github.io/bggn213_W23//class-material/bioconductor_setup/){:.no-push-state}{:target="_blank"} instructions.
- WebApp: [Introduction to PCA](https://bioboot.github.io/bggn213_W23/class-material/pca/){:.no-push-state}{:target="_blank"},  
- [Muddy point assessment](https://forms.gle/DjpHctStFB15vaow6){:.no-push-state}. 


**Readings**:
 - Excellent review article: [Conesa et al. A survey of best practices for RNA-seq data analysis. _Genome Biology_ 17:13 (2016)](http://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0881-8){:.no-push-state}.  
 - An oldey but a goodie: [Soneson et al. "Differential analyses for RNA-seq: transcript-level estimates improve gene-level inferences." _F1000Research_ 4 (2015)](https://f1000research.com/articles/4-1521/v2).  
  


**Homework:**
- Submit your completed PDF lab report to [GradeScope](https://www.gradescope.com/courses/528106){:.no-push-state}{:target="_blank"},  


--- 
<a name="2"></a>
## Class 2: RNA-Seq analysis mini-project

**Topics:** 
Differential expression analysis project, Working with GEO and DESeq2 followed by gene enrichment and functional annotation with KEGG and GO ontologies.   


- Lab: [DESeq2 analysis mini-project]({{ site.baseurl }}/class_material/class2_lab.html){:.no-push-state}{:target="_blank"}.  
- [Muddy point assessment](https://forms.gle/nTcwUHM4c2nmNZvp8){:.no-push-state}.  TO UPDATE


**Homework:**
- Submit your completed PDF lab report to [GradeScope](https://www.gradescope.com/courses/528106){:.no-push-state}{:target="_blank"},  
