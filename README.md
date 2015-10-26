# intermine2heatmap

Takes a table formatted as follows



    geneid   transcriptid    sra_accession    tissue   brenda_term  fpkm  raw_counts



And transforms it into a heatmap based on the transcript IDs and the FPKM values (log10 transformed)


## Usage

    intermine2heatmap input.tsv output.png

