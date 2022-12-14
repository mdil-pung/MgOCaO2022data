This is the data repository for the publication of K. Lee, Y. Park, and S. Han:

[*Ab initio* construction of full phase diagram of MgO-CaO eutectic system using neural network interatomic potentials](https://journals.aps.org/prmaterials/abstract/10.1103/PhysRevMaterials.6.113802).

## Data description
- NNP models trained from PBE or SCAN functional `MgOCaO_2022_Lee.*.nnp`
- VASP OUTCARs used to train SCAN-NNP as split-compressed tarballs `SCAN_data_MgOCaO_2022_Lee.tar.gz*`

## Usages
- The NNP models are compatible with LAMMPS after implementing SIMPLE-NN code.
- Installation, manual, and full details of SIMPLE-NN: https://simple-nn-v2.readthedocs.io
- To unpack the split-compressed tarballs in linux, try to use the following command: `cat SCAN_data_MgOCaO_2022_Lee.tar.gz* | tar zxvf -`.
