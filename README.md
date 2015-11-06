# intermine2heatmap

Takes a table formatted as follows



    transcriptid    tissue   fpkm



And transforms it into a heatmap based on the transcript IDs and the FPKM values (log10 transformed)


## Usage


### Heatmap

    intermine2heatmap input.tsv output.png|pdf|html

This will output a png, pdf (with heatmap.2), or html page (d3heatmap) with your output.

### Clusters

    intermine2clusters input.tsv clusters_filename_prefix num_clusters

This will generate `clusters_filename_prefix.txt` and `clusters_filename_prefix.png`
