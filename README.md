# slurmOnitor

## About

a slurm cluster load monitor

## License

Copyright (c) Sven E. Templer 2015

## Usage

check `slurm` variable (`False` for ssh queries)
run './slurmOnitor' to start

## Issues

Issue when using module to change python path
solved by the following:

`export PYTHONUSERBASE="$HOME/.local"`
