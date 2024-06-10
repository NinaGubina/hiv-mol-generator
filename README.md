# Generation of molecules capable of inhibiting HIV replication

This repository contains code for training variation autoencoder (VAE) and conditionally variation autoencoder (CVAE) on an example dataset obtained from the [MoleculeNet](https://moleculenet.org/) resource provided by [DeepChem](https://deepchem.io/). The dataset consists of molecular structures labeled according to their activity in suppressing HIV replication.

The code to implement the VAE was taken from the `genmol` [repository](https://github.com/bayeslabs/genmol/tree/master)  and then modified to implement directed generation using CVAE.


