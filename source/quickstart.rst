==========
Quickstart
==========

Execute workflow: Test your configuration by performing a dry-run *via* snakemake -n

Execute the workflow locally *via*

* snakemake --cores num_cores
where num_cores are the number of available cores on your machine *e.g.* 4

or run it in a cluster environment such as
snakemake --use-conda --cluster qsub --jobs 100

Further information on running snakemake in different cluster environments can be found on the snakemake website
https://snakemake.readthedocs.io/en/stable/
