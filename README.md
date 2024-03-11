#16S rRNA related testing of nanopore sequences

Original sequence is from Petrone et al article 2023 (https://doi.org/10.3389/fmicb.2023.1201064)

Rrn operon reads were truncated by 1492R primer to contain solely 16S rRNA sequence

Reads were imported to Qiime 2 (version 2024.2) and either denoised by dada2 or dereplicated and clustered with vsearch. In latter case, chimeras and singletons were removed after clustering.

Data analysis is quarto document (qmd). Results have been rendered to pdf and MS Word docx files.
