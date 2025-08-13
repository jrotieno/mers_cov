# Nextclade dataset files for MERS-CoV

Put these files here:
- pathogen.json
- reference.fasta        (header: >NC_019843.3)
- genome_annotation.gff3 (seqid matches FASTA header; CDS phases numeric)
- tree.json              (Auspice v2; rooted on the reference tip; ref tip has no branch muts)

Test:
```bash
nextclade run --input-dataset . --output-all out ../../../test_data/example.fasta