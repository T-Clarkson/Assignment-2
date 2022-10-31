# Assignment-2

This repository was used for the purpose of the BIOL3207 Assignment 2.

File Summary

assignment2.Rmd - R Markdown file containing the code used in creating the assignment

assignment2.Rproj - The R Project file

assignment2.html - The HTML created by knitting 'assignment2.Rmd'

clark_paper_data.csv - Metadata from Clark et al paper (2020)(https://doi.org/10.1038/s41586-019-1903-y)

meta-data_ocean_meta.csv -  Contains descriptors for the columns of 'ocean_meta_data.csv'

ocean_meta_data.csv - Contains the main metadata of ocean acidificaion effects on activity in fish



Work Flow

-Tidied 'clark_paper_data.csv' and generated summary statistics. This was then merged with 'ocean_meta_data.csv' to create a collection of all of the metadata.
-Meta-analytical models were generated using the merged dataframes and statistics from these are referenced throughout the 'assignment2.html' report.
-Figures are generated using meta-analytical models and data the merged dataframe.
