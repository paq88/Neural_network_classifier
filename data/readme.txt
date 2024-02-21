Data used, 

Bacteria abduance for gut samples
- (folder - gut) - original dataset with .tsv different files for different ponds. Coded - Gut_S(pond_number). (One file - one pond, bacteria as rows, different samples from one pond as columns, abduance in cells)
- (folder - gut_csv_no_head) - transformated to .csv format.
- (file - gut_full_feature_table.csv) - transposed and joined form of all feature tables from previous files. Bacteria as columns, samples as rows, abduance in cells. 

KEGG  paths 
- (file - KEGG_paths.tsv) - KEGG paths abduance file with joined samples from all ponds. Paths as rows, samples as collumns coded as follows S.(pond_number).(sample_number).Gut

Orthology 
- (folder - orgologs) - Abduance of ortologs for different ponds. 25 files for ponds in .tsv format. ortologs as rows, samples from pond as columns.
- (file - ortologs_full_table.csv) transposed joined version in .csv format. ortologs as columns, samples as rows.
