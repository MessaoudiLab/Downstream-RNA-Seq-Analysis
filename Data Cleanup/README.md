# Clean up edgeR data (bulk RNA-Seq) 
1. Filter data based on FDR ≤ 0.05, p-value ≤ 0.05 and logFC ≥ 1 OR ≤ -1
2. Optional: Can further filter data by applying an average RPKM cutoff (RPKM 1 or 5 commonly used)
3. Optional: Can further filter data by removing noncoding RNA genes (i.e. rRNA, 7SK RNA, Y RNA, spliceosomal RNA, SNORA, SCARNA)

Make sure to keep copies of both rawdata and filtered data
