# Marcus-Hush-Chidsey DOS rates in twisted Trilayer Graphene system

Using ElectrochemicalKinetics.jl to calculate rates in tTLG system

## Usage

```
script.jl # Outputs a .mat file with kox (kox_list), kred (kred_list), theta12 (q12_list) and theta23 (q23_list) variables
# for given <prefactor>_<lambda>_<eta>

eta_run_script.jl # Runs script.jl at a range of eta values

# The output mat file has a format: k_data_<prefactor>_<lambda>_<eta>.mat
# where lambda = reorganization energy (eV), eta = applied overpotential (V)

sweep/ # Contains the .mat DOS files of	tTLG system at a range of theta12 and theta23.

sweep_dos.m # Uses output .mat file to generate colormaps of k<red/ox> for given <prefactor>_<lambda>_<eta>

Ruhex_data/ # Contains k_data_1.0_0.82_<eta>.mat and colormaps(k<ox/red>_<eta>.png) for analyzing MHCD rates of Ruhex with tTLG.
```





