# Preparing for Functional Enrichment 
Once edgeR is complete, the program would have created an excel file containing all information pertaining to DEG’s. A Mastersheet must be created to organize the various timepoints of the experiment and it must include an rpkm average for each day. After this is complete, transfer all information to a different workbook that has filtered values of the data. These include:
- rpkm average 
- fdr ≤ 0.05
- p-value ≤ 0.05
- logFC ≥ 1 OR ≤ -1

Next, transfer all data from the filtered Mastersheet to a different workbook titled proteincoding. This is where all genes regarding RNA must be deleted because only the genes that directly affect proteincoding are essential to specific biological pathways. All genes that must be deleted include:
- SCARNA
- SNORA
- SNORD
- snou
- Splicesome RNA
- Y RNA
- 7SK

Now, filter the Log FC value to ascending so that up and down regulated values are clearly distinguishable. On seperate workbooks, organize a column for Gene and for LogFC between all up regulated and down regulated genes for each timepoint.
