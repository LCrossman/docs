========
Tutorial
========

1. Edit config.yaml to include the following:
threads:
      4
download_genbank:
      options: "no"
tree_type:
      options: "fasttree"
protein_dna:
      options: "protein"
report:
      "report.html"
previous_files:
      "previous.fasta"

2. Create genus.txt to include only the following (do not omit the quotes):

"Staphylococcus argenteus"


3. Assure all the files are available in the correct folder and include an empty file named "previous.fasta"

4. run:

  snakemake --cores 4   (if 4 cores, 8 threads, are available)

5. Have a hot drink and wait for the results!
