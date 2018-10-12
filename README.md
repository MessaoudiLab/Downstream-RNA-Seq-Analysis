# Downstream Analysis
## Preparing for Functional Enrichment
Once edgeR is complete, the program would have created an excel file containing all information pertaining to DEG’s. A Mastersheet must be created to organize the various timepoints of the experiment and it must include an rpkm average for each day. After this is complete, transfer all information to a different workbook that has filtered values of the data. These include:
- rpkm average ≥ 5
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

## Functional Enrichment
Functional Enrichment is used to cluster genes that are associated with specific biological pathways. 
```
1. Save an excel file with 2 columns (gene name and -logFC)
2. Log on to MetaCore and select Experiments
3. Select Andrea
4. Upload excel file under upload
5. Upload experiments with gene or protein ID's
6. Upload file as .xls
7. Next
8. Homosapiens
9. Select workflows and reports
10. Enrichment analysis
11. Next
12. Set p-value to 0.05
13. Apply
14. Select top 100 genes for all
15. Save workflow (end name of workflow with enrichment analysis)
16. Get report
```
