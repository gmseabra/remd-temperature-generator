# Temperature generator for REMD simulations

This is based on work published in:

Alexandra Patriksson and David van der Spoel, *"A temperature predictor for parallel tempering simulations"*, [Phys. Chem. Chem. Phys., 10 pp. 2073-2077 (2008)](http://dx.doi.org/10.1039/b716554d). 

A running version of the webserver is here:

~http://virtualchemistry.org/remd-temperature-generator/~

## Note
As of 03-10-2021, the remd server is not working. In order to run it locally, you need to install a php-command line interface. In RHEL, the one available was `php-cli.x86_64`, version 7.2.24-1, and can be installed with:

```
$ sudo yum install php-cli.x86_64
```
After installing php, just go to the `remd-temperature-generator` directory, and run 

```
php -S localhost:8000
```

You can then access the server on your browser going to http://localhost:8000, fill in the parameters and click submit to get the temperatures.

# For other information on REMD, look at:

1. [AMBER Tutorial](http://ambermd.org/tutorials/advanced/tutorial7/index.php) on Replica Exchange Molecular Dynamics 
1. *"Replica Exchange Molecular Dynamics: A Practical Application Protocol with Solutions to Common Problems and a Peptide Aggregation and Self-Assembly Example"*, [Methods Mol Biol. 2018; 1777: 101–119](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6484850/)
2. *"Improving Temperature Generator in Parallel Tempering Simulation in the NPT Condition"*,[J. Chem. Theory Comput. 2020, 16, 3, 1827–1833](https://doi.org/10.1021/acs.jctc.9b00984)
3. *"Modified Replica Exchange Simulation Methods for Local Structure Refinement"*, [J. Phys. Chem. B 2005, 109, 16, 8220–8230](https://doi.org/10.1021/jp045437y)
