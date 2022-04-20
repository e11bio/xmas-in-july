# epitope assembler

Generating epitope tags for gene block synthesis + cloning with a specified linker between epitopes and upstream of the KI tag.
Does not include cloning handles or stop codon.
Currently does no codon optimization; generates only AA sequences.

DNAChisel (for codon optimization; forward thinking) can be installed via pip; conda install is broken for reasons unclear.

# Wish list

- [ ] convert AA -> codon optimized DNA (DNA chisel)
- [ ] fragment generator, avoiding cloning handles within &c (DNA Chisel) and adding DNA tails for KI
- [ ] plasmid assembler (final map -> Genscript/cloning CRO) (dna chisel or pydna?)
- [ ] primer design step (sanger; NGS; whole plasmid?
