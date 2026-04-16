# Global temperature shocks and damage functions

This repository hosts the global temperature shocks as well as the estimated global and regional damage functions from the paper:

Adrien Bilal and Diego R. Känzig (2026)  
Forthcoming, *Quarterly Journal of Economics*  
Published version: https://doi.org/10.1093/qje/qjag011  
Ungated version: https://dkaenzig.github.io/diegokaenzig.com/Papers/bk_micc.pdf  

This repository contains two main folders:

### 1. Damage functions
This folder contains:
- `DamageFunctions.csv`: Estimated damage functions up to horizon \( h = 20 \)
- `DamageParameters.csv`: Estimated damage function coefficients for A, B, and C
- `OutputPath.csv`: Simulated output path under a business-as-usual scenario

### 2. Temperature shocks
This folder contains:
- `temperatureShocks_pwt.csv`: Constructed temperature shocks for the PWT sample (1960–2019)
- `temperatureShocks_bu.csv`: Constructed temperature shocks for the BU sample (1860–2019)

A repo with the full replication files can be found here: https://github.com/dkaenzig/micc_replication

For questions, please contact the authors at dkaenzig@northwestern.edu and adrienbilal@stanford.edu

## License

The data are licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

The code in this repository is licensed under the [BSD 3-Clause License](https://opensource.org/license/BSD-3-Clause).

You are free to share and adapt the data and code provided appropriate credit is given. If you use these data or code, please cite the following paper:

Bilal, Adrien and Känzig, Diego R. (forthcoming).  
The Macroeconomic Impact of Climate Change: Global Versus Local Temperature  
The Quarterly Journal of Economics  
https://doi.org/10.1093/qje/qjag011  

```bibtex
@article{bilalkanzig2026macroeconomic,
  title   = {The Macroeconomic Impact of Climate Change: Global Versus Local Temperature},
  author  = {Bilal, Adrien and K{\"a}nzig, Diego R.},
  journal = {The Quarterly Journal of Economics},
  year    = {2026},
  note    = {Forthcoming},
  doi     = {10.1093/qje/qjag011}
}
```
