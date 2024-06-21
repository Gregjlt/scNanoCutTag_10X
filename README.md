# Single-cell nano CUT&Tag 10X pipeline

This data engineering pipeline is designed to treat single-cell nano CUT&Tag 10X
with protocol design from the Institut Curie SingleCellOmics Platform and Vallot Lab.
The dataset starts from raw BCL sequencing files to exploitable output such
as count matrices, coverage file and report.  


To launch the pipeline : 

.run_multiple_samples.sh path/to/samplesheet

the pipeline will first create a config file, and then launch the script schip_processing.sh. Functions called in schip_processing.sh are mainly stored in scripts/func.inc.sh


