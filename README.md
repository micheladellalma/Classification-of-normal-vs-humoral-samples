# Classification-of-normal-vs-tumoral-samples
Analysis of the TCGA gene expression data with classification techniques

Steps:

1) The GenoSurf (http://geco.deib.polimi.it/genosurf/) interface has been used to download the data, using the following option selection:
- project_name: ['tcga-brca']
- assembly: ['grch38']
- data_type: ['gene expression quantification']
- - is_healthy:
- ['false'] for tumoral data
- [true] for normal data.

2) Analysis input file (Exploratory Data Analysis)

3) Split the data into train and test sets.

4) Run different classification techniques and compare them by using different evaluation metrics (accuracy, precision, recall,...)

5) Usage of k-fold cross validation
