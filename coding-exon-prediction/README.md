coding_exon_prediction 

- Predicts coding exons based on a protein reference from all genomes within a list of genome directories.
- Will predict and translate best aligned coding exons using exonerate protein2genome model. 


	Usage: ./coding_exon_prediction.sh  [dir_list.txt]  [protein_query.fasta]  [best_n_hits]  [masked_query(Y/N)]  [trans_table(standard=1)]  [gene_id]


Requires in $PATH: Exonerate, Transeq(EMBOSS), longest_orf.py, extract_exonerate_output.py 

Written in bash: version 4.4.12(1)-release (x86_64-pc-linux-gnu)
