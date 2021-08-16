# MobileGeneticElementDatabase
Contains a fasta format database of a large variety of mobile genetic elements MGEs_FINAL_99perc.fasta.tar.gz and an annotation file MGE_tax_table.txt

The custom MGE database was created by fetching CDS for genes that were annotated as IS*, ISCR*, intI1, int2, istA*, istB*, qacEdelta, tniA*, tniB*, tnpA* or Tn916 transposon ORFs or genes in the NCBI nucleotide database and it also includes the PlasmidFinder database. Redundancy in the databases was removed with VSEARCH17 -usearch_global command with --id 99 option and sequences longer than 4000 bp or shorter than 100 bp were excluded from the database. In total, the MGE database consists of genes with 278 different gene name annotations and more than 2000 unique sequences excluding the sequences from PlasmidFinder database.

Cite
Pärnänen K, Karkman A, Hultman J, Lyra C, Bengtsson-Palme J, Larsson DGJ, Rautava S, Isolauri E, Salminen S, Kumar H, et al. Maternal gut and breast milk microbiota affect infant gut antibiotic resistome and mobile genetic elements. Nature Communications 2018;9:3891. 

