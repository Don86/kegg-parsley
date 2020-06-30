# polyglot

Grabs the content of as many DBs as I can think of and returns them in a sensical JSON format, *just the way God intended it*. If these DBs have APIs attached to them, this is then a thin-layer over the relevant GET or POST request. 

### Quickstart

Use `db_list()` to see what DBs have been included.

### Implemented DBs:

* MetaboAnalyst, KEGG, Uniprot, NCBI efetch (without using BioPython), Pubchem, BIGG, BioModels.

### Developer Notes

* This was also meant to teach myself `pytest`, and CI/CD with `TravisCI`.

### Caveats

* KEGG - heavily depends on the fact that the first 12 spaces of each line are either a key or a single white space `\s`. 