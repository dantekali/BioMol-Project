# Molecular Biology

### Computational analysis Project

*Dante Aviñó, Miguel Borge, Pol Segura*

------

The main objective of the project is to **annotate the genes** included in the contig and to **functionally characterize** the predicted proteins.

Download assigned contig from a nematode species.

```bash
# Using npm package manager we're going to install github-files-fetcher
# so we can download particular files from the github repo.
npm install -g github-files-fetcher

# Download contig sequence from repo
fetcher --url="https://github.com/dantekali/BioMol-Project/blob/main/Group11_contig_194888_195063.fa"  --out="~/Desktop/Project"
```

Annotate the genes included in the contig and to functionally characterize the predicted proteins.

- **ab-initio tools** to obtain a first prediction (select closest species in model)

  - https://bio.tools/t?page=1&q=%27Ab-initio%20gene%20prediction%27&sort=score
  - https://ibb.co/bdznRS4

- **blast search** to identify the putative proteins (more sensitive if protein level instead of nucleotides)
- **homology-based tools** with the annotations of  a closely related species (web-server/local)
  - https://bio.tools/t?page=1&q=%27Homology-based%20gene%20prediction%27&sort=score
  - https://ibb.co/vqymcSd

Discuss the performance of the different methods. Can you guess to which species does
your contig correspond?