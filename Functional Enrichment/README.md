# Functional Enrichment
## MetaCore
Functional Enrichment is used to cluster genes that are associated with specific biological pathways. 
```
1. Create an excel file (as .xls) with 2 columns: 1st containing the hgnc or gene ID and 2nd containing the fold change
2. Log on to MetaCore (https://portal.genego.com/cgi/data_manager.cgi) 
3. Click "Upload"
4. Click "Upload experiments with Gene or Protein IDs"
5. Choose file and click Next
6. Choose Homosapiens
7. After data has been uploaded, return to start page and refresh the page
8. Check that the data to be analyzed has a green check mark
9. Click "Workflows & Reports"
10. Click "Enrichment Analysis"
11. Check the correct data is selected for analysis and click Next
12. Set p-value to 0.05 and click Apply
13. Change the number of GO terms to be displayed
14. Save workflow (end name of workflow with enrichment analysis)
15. Get report
```

### Download and Clean up a MetaCore Export
```
1. In Metacore, download Functional enrichment term by clicking on the green number to the right
2. To clean up, list all items in the column, Input_ID, in ascending order. 
3. Copy Input_ID column and Fold change column into a new tab in excel
4. Remove duplicates
```

## MetaScape
Follow the commands down below
```
1. GO to website: http://metascape.org/gp/index.html#/main/step1
2. Upload list of genes (hgnc symbol)
3. Select custom analysis
4. Select enrichment
5. Uncheck all boxes except GO Biological Processes
6. Select enrichment analysis
7. Select analysis report page
8. Select all in one zip file
9. Rename zip file to desired name
```

##EnrichR
```
1. Go to website:https://amp.pharm.mssm.edu/Enrichr/
2. Copy an paste list of genes (hgnc symbol) and click submit
3. Click "Ontologies" on the top
4. Click "GO Biological Process"
5. Click "Table"
6. Click "Export entries into table"
```
