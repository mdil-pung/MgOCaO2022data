This is the data repository for the publication:

[*Ab initio* construction of full phase diagram of MgO-CaO eutectic system using neural network interatomic potentials](https://arxiv.org/abs/2208.11863).

## Data description
- NNP models trained from PBE or SCAN functional `MgOCaO_2022_Lee.*.NNP`
- VASP OUTCARs used to train SCAN-NNP as split-compressed tarballs `PRM_2022_SCAN_OUTCAR_Lee.tar.gz*`

The NNP models are compatible with SIMPLE-NN code.
Installation, manual, and full details: https://simple-nn-v2.readthedocs.io

To unpack the split-compressed tarballs in linux, try to use the following command:

`cat PRM_2022_SCAN_OUTCAR_Lee.tar.gz* | tar zxvf -`.
