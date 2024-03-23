# BiotDDMortar
## Modified version of BIotDD with more functions added. Later need to be merged with BiotDD.

__Note__: If you use the code for research or development, please cite the following original publications: [Domain decomposition and partitioning methods for mixed finite element discretizations of the Biot system of poroelasticity M Jayadharan, E Khattatov, I Yotov Computational Geosciences 25, 1919-1938](https://link.springer.com/article/10.1007/s10596-021-10091-w)
and
[Multiscale mortar mixed finite element methods for the Biot system of poroelasticity M Jayadharan, I Yotov arXiv preprint arXiv:2211.02949](https://arxiv.org/abs/2211.02949)

### This is currently the most generic repository with all functionalities including all three schemes (monolithisc, DS, FS), mortar and mulstiscale basis capability, gmres for all differenet schemes, with all the latest fixes. 
Refer to https://github.com/mjayadharan/BiotDD for more details and compilation instructions. 
Biot DD without mortar works for all latest versions of deal.ii, while the one with mortar works only for deal.ii versions <9.0
