Introduction
============
    This document is intended to specify a set of requirements 
    for the project OMG, which means "Oh My Genes", a web 
    application for identifying genes' expression differential.


Purpose
-------
    To identify differentially expressed genes given a gene 
    expression file containing two cell samples. The main 
    purpose is to help biologists analyze their experiment
    data. 


Overview
--------
    The web application has a simple interface with a single button 
    [Upload and GO]. Our scientists upload a plain text file 
    containing gene expression levels from two samples, representing 
    two experimental conditions. Accepting the file, the software
    will return a table of differentially expressed genes 
    and a scatter plot of these genes whose X-axis is control 
    and Y-axis is treatment. If an invalid gene expression is given, 
    the web application returns a page informing the user to provide 
    the correct format. 


User Characteristics
--------------------
    *   **Client User:** Biologists who devote themselves studying the expression of genes.
    *   **Site Maintainer:** Technicians who have the basic knowledge of flask and python to maintain a website.


Terminologies & Abbreviations Explaination
------------------------------------------
    To introduce the project and specify the requirements in detail, 
    this section is aimed to explain some terminologies and abbreviations, 
    for the sake of better understanding of the content of the project. 

Terminologies
~~~~~~~~~~~~~
    *   *Control sample* - A cell sample prepared in its normal condition.
    *   *Treatment sample* - A cell sample treated by special chemicals, or in which some genes are altered.
    *   *Differentially expressed genes* - The genes which have significantly different expression levels between two samples.
    *   *Up-regulation* - A gene is said to be up-regulated if it has higher expression in treatment than in control.

Abbreviations
~~~~~~~~~~~~~
    *   *OMG* - Oh My Genes, which is the name of this project. 
    *   *logFC* - log fold change of gene expression. log_2 [T/C], where T is the gene
        expression level from a treatment sample, while C is the gene expression level from a
        control sample
