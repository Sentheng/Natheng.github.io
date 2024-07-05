---
title: "Predicting Genomic Anomalies with Generational Genomic Signals"
permalink: /publication/Predicting-Genomic-Anomalies-with-Generational-Genomic-Signals
excerpt: 'Created and implemented convolutional neural networks and transformer architecture using PyTorch to predict structural variants (SVs) within an individual’s genome. This project utilized low-quality observation signal data from nine related family members that were transformed into a 3x3 image and fed through the architecture. The results indicate 67.87% accuracy. The abstract is under review for the Asilomar Conference on Conference on Signals, Systems, and Computers. (Research Advisor: Dr. Mario Banuelos, Department of Mathematics)'
date: 2024-02-17
venue: 'Asilomar Conference on Conference on Signals, Systems, and Computers'
paperurl: 'https://NathanTheng.github.io/files/Asilomar_Extended_Summary.pdf'
citation: 'Theng, et al. (2024). &quot;Predicting Genomic Anomalies with Generational Genomic Signals.&quot; <i>Asilomar Conference on Conference on Signals, Systems, and Computers</i>.'
---

Abstract: The human genome consists of sequences of nucleotides (A,T,G,C) spanning billions of base pairs. Due to the evo- lutionary processes of mutation, variation may be present between different genomics samples in the form of single nucleotide variants (SNVs) or observable differences spanning a larger region of DNA known as structural variants (SVs). SVs are found in the form of deletions, inversions, insertions, and duplications. Although the prevalence of such genomic variation promotes genetic diversity, it can also be associated with genetic diseases such Autism and Alzheimer’s disease. SVs can potentially impact gene expression, resulting in al- tered phenotypes and possibly cancer, making it very important to develop accurate detection models.

In our work, we implement both neural network and binary classification machine learning models and assess their ability to identify the presence of a true deletion within an individual’s genome. We compare the predictive analytics of a Convolutional Neural Network (CNN) and Logistic Regression in identifying such variation using genomics signals of related family members. We utilize a low-quality dataset that holds information about the number of DNA fragments at specific genomics locations. The data used for our study was obtained from the 1000 Genomes Project and includes information about a three-generation, 17-member family.
