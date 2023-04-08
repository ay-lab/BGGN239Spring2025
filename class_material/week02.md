---
layout: page
title: Week 2 - FERHAT AY
menu: false
description: >
  **Key Point:** To fully participate in the hands-on sections of this course you will need to refresh your R and UNIX skills as well as have access to [specific software]({{ site.baseurl }}/setup/) on your own laptop that you bring to each class.
---

> ### On this page:
- Class 0: [Getting oriented](#0).
- Class 1. [Transcriptomics and the analysis of RNA-Seq data](#1).
- Class 2: [RNA-Seq analysis mini-project](#2).

<br/>

<a name="0"></a>
## Class 0: Getting oriented  

**Topics:**  
Course introduction, Learning goals & expectations, Meet the instructional team. Seting up your computer with required software. Refresh your knoweledge of basic UNIX and R.  


**Goals:**
- Understand course scope, expectations, logistics and ethics code.  
- Setup your computer for this course.  
- Familiarity with major R data structures (vectors, data.frames and lists),
- Understand the basics of using R functions (arguments, vectorizion and re-cycling).
- Be able to install R packages from CRAN and BioConductor.  
- Use UNIX command-line tools for file system navigation and text file manipulation.  


**Supporting material:**  
- Handout: [Class Structure](https://ay-lab.github.io/BGGN239Spring2023/class_material/Class_Overview.pdf){:.no-push-state}{:target="_blank"},  
- Computer [Setup Instructions]({{ site.baseurl }}/setup/). 


**Optional Recap Videos from BGGN213:**
- 0.1.1 - [Introduction to bioinformatics (what, where and why of bioinformatics)](https://youtu.be/75JGKKZ7oNM){:.no-push-state}{:target="_blank"},  
- 0.1.2 - [Major bioinformatics resource providers (NCBI and EBI)](https://youtu.be/o_IO7dDUZPM){:.no-push-state}{:target="_blank"},  
- 0.1.3 - [A quick tour of the GENE, UniProt, GO, OMIM, PDB and PFAM](https://youtu.be/afqB87ZSkXw){:.no-push-state}{:target="_blank"}.    


- 0.2.1 - [Major R data structures, data types, and using functions](https://youtu.be/GRKdOPVD3-Y){:.no-push-state}{:target="_blank"},  
- 0.2.2 - [Introduction to ggplot](http://youtu.be/c8wWtU3aoF4){:.no-push-state}{:target="_blank"},   
- 0.2.3 - [Introduction to CRAN & BioConductor](https://youtu.be/qAvJ92qCGqE){:.no-push-state}{:target="_blank"},
- 0.2.4 - [Quick introduction to RMarkdown](https://www.youtube.com/watch?v=O7GMs9V3HQk){:.no-push-state}{:target="_blank"},  


- 0.3.1 - [Essential UNIX for bioinformatics I](http://youtu.be/qsDzjQm_Wp0){:.no-push-state}{:target="_blank"},  
- 0.3.2 - [Essential UNIX for bioinformatics II](http://youtu.be/11t1GuZB77M){:.no-push-state}{:target="_blank"},  
- 0.3.3 - [Manipulating files on UNIX machines](http://youtu.be/_jVgj6UutwA){:.no-push-state}{:target="_blank"}
- 0.3.4 - [UNIX superpowers: using pipes and conecting to remote machines](http://youtu.be/AKLha-_IurU){:.no-push-state}{:target="_blank"}.  



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
