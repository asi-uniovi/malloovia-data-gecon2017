# Malloovia - Data for GECON 2017

This repository contains the data used in the paper "Cost Minimization of Virtual Machine Allocation in Public Clouds Considering Multiple Applications" presented in [GECON2017](http://2017.gecon-conference.org/).

The data consists of three data sets, each one in its own directory:

- **problems**: the problems with the workload and the infrastructure.
- **sol_phase_i**: the solutions for Phase I.
- **sol_phase_ii**: the solutions for Phase II.

In each data set, there is a file for each quantization amount, as shown in table 2 in the paper. The files are distributed following a [YAML format defined in Malloovia](https://malloovia.readthedocs.io/en/latest/yaml.html).

The Jupyter Notebook [Malloovia-Gecon2017-data.ipynb](Malloovia-Gecon2017-data.ipynb) shows how to generate the results from the problems using [Malloovia](https://github.com/asi-uniovi/malloovia).
