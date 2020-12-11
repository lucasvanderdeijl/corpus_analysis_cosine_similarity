# Corpus Analysis with Cosine Similarity

Author: Lucas van der Deijl, University of Amsterdam <br/>
Version: 9 December 2020 <br/>
Contact: l.a.vanderdeijl@uva.nl, www.lucasvanderdeijl.nl <br/>
Project: 'Radical Rumours' (Funded by NWO 2017-2021) <br/>

## Aim of this program

The program offers a basic method to analyse textual similarity between document pairs from either one corpus or two different corpora. Textual similarity is formalised as [cosine similarity](https://www.sciencedirect.com/topics/computer-science/cosine-similarity) based on [tf-idf values](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) for every word type in the corpus. The results are visualised as a heatmap and can be stored as a csv-file.

This Jupyter notebook can be used to reuse the code or to replicate the analysis with different corpora. Run each code block individually or use the 'Run all'-option from the Cell-tab.

## Pipeline
The pipeline desigend to achieve the program's aim performs the following steps:

+ import the required modules
+ install missing libraries (if needed)
+ define functions for preprocessing and parsing
+ define the filepath to the location of your corpus
+ load and preprocess your corpus
+ create a term-document matrix with tfidf values
+ creae a document-document matrix with cosine similarity values
+ visualise the document matrix as a heatmap
+ store the output
