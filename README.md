# High-quality and universal empirical atomic charges for chemoinformatics applications

## Links
[Paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-015-0107-1) in Journal of Cheminformatics

## Corresponding authors
Radka Svobodová, Ph.D. ([email](mailto:radka.svobodova@ceitec.muni.cz))

## EEM method and its parameterization
Description of EEM method and its parameterization is covered by this [document](eem.pdf).

## Getting parameters
EEM parameters were calculated for the following QM methods:
- HF/6-311/MPA
- HF/6-311/NPA
- HF/6-311/AIM
- B3LYP/6-311/MPA
- B3LYP/6-311/NPA
- B3LYP/6-311/AIM

All the parameters can be downloaded in one archive [parameters.tar.gz](parameters.tar.gz).

## Using EEM parameters to calculate charges
1) [Atomic Charge Calculator II](https://acc2.ncbr.muni.cz)

2) OpenBabel (use `--partialcharges {eem2015ba, eem2015bm, eem2015bn, eem2015ha, eem2015hm, eem2015hn}`)
