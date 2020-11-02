Pipelines developed to predict genes from draft genomes



coding-exon-prediction

coding_exon_prediction.sh is a pipeline that will predict coding-exons based on a protein reference
using the protein2genome model in exonerate. All predictions are translated using transeq(EMBOSS) and the longest
open reading frames identified using longest_orf.py (see Sequence-tools)

  
  Usage: ./coding_exon_prediction.sh  [dir_list.txt]  [protein_query.fasta]  [best_n_hits]  [masked_query(Y/N)]  [trans_table(standard=1)]  [gene_id]




hmm_to_fasta

hmm.sh is a pipeline that builds an hmm profile from a nucleotide or protein query multi-fasta file then searches through a target genome and
using hmm_to_fasta.py (see Sequence-tools) returns the hit sequence.


  Usage: ./hmm.sh  query.fasta  target.fasta  P/N  id





