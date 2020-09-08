## Some supporting materials for the published paper "Unsupervised Fuzzy Pattern Discovery in Gene Expression Data"

Citation: Wu, G. P., Chan, K. C., & Wong, A. K. (2011, December). Unsupervised fuzzy pattern discovery in gene expression data. In BMC bioinformatics (Vol. 12, No. 5, pp. 1-9). BioMed Central.

Link to paper: https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-12-S5-S5


The original colon-cancer data set: http://genomics-pubs.princeton.edu/oncology/affydata/index.html
(You can also find the underlying files in the /data/alon/ in this repository.)

Top 10 patterns of colon cancer data set: https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-12-S5-S5/figures/3

Method: https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-12-S5-S5#Sec2

Java implementation of attribute clustering algorithm: https://github.com/GeneWu/MPDA/blob/master/maca/src/mixedmodeaca/AttributeClustering.java
This can generate the table that contains all normalized redundancy values among attributes. Then, formula (6), fuzzy membership function, in "attribute cluster fuzzification" section of https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-12-S5-S5#Sec2 can be applied to calculate the fuzzy membership.
