# PrimaryCareScientometrics
R and Python Files for Characterizing Primary Care Research Outputs/Impacts 

This repository contains several Jupyter Notebooks which showcase a computational pipeline for research program evaluation. We imagine these notebooks may be of value to data scientists, computational researchers, and others interested in research program evaluation. The notebooks are labelled in a sequential order, and are meant to be run/executed in a sequential order.

The notebooks make use of a number of R/Python libraries, including:
- rscopus: for querying author publication information from the Scopus API.
- rAltmetrics: for querying altmetrics information from the Altmetrics API.
- sklearn: for unsupervised topic modelling.
- NLTK: for natural language processing.
- igraph: for network scientific modelling and analytics.

The input to these sequential notebooks are a few hundred Scopus IDs (unique to a given author). As a primary care biostatistician, we focused on extracting N=658 Scopus IDs corresponding to researchers embedded within one of seventeen international primary care research institutions (from Canada, the United States, the United Kingdom, Australia, and Asia). The goal of our analyses were to characterize research outputs/impacts generated from researchers embedded within these select primary care institutions.

A manuscript further documenting our study methodology and findings has been submitted for publication in a peer reviewed scientific journal. Once published we will provide a link/URL to these works on this GutHub repository.

If you would like to discuss this project further, please reach out at: christopher [dot] meaney [at] utoronto [dot] ca
