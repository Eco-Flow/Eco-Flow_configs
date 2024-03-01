# configs
A repository to store config files set up for specific HPCs.

These are designed to work in tandem with the configs written for each Eco-Flow pipeline and as such should be supplied to a pipeline as follows:

`nextflow run main.nf --custom_config /url/to/raw/github/file`

**Do not use the `-c` option as that overrides the default configs in the pipeline.**
