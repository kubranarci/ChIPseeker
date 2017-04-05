# ChIPseeker
an R package for ChIP peak Annotation, Comparison and Visualization

Depends >= 3.3.0
 This package implements functions to retrieve the nearest genes
around the peak, annotate genomic region of the peak, statstical methods
for estimate the significance of overlap among ChIP peak data sets, and
incorporate GEO database for user to compare the own dataset with those
deposited in database. The comparison can be used to infer cooperative
regulation and thus can be used to generate hypotheses. Several
visualization functions are implemented to summarize the coverage of the
peak experiment, average profile and heatmap of peaks binding to TSS
regions, genomic annotation, distance to TSS, and overlap of peaks or
genes.

Usage:

R chipseeker.r [options] peak_file TxDb_object

[options]

# 1. upstream value : default is 3000
# 2. downstream value : default is 3000


