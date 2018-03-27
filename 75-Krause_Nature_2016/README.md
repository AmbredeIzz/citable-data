Supporting information for: [“A pressure-amplifying framework material with negative gas adsorption transitions”](https://doi.org/10.1038/nature17430), S. Krause, V. Bon, I. Senkovska, U Stoeck, D. Wallacher, D. M. Többens, S. Zander, R. S. Pillai, G. Maurin, F.-X. Coudert, and S. Kaskel, _Nature_, **2016**, 532, 348–352, DOI: [10.1038/nature17430](https://doi.org/10.1038/nature17430)


**Videos:**

- [`supplementary video 1.wmv`](supplementary%20video%201.wmv): Visualization of a framework material during NGA. This video clip shows macroscopic movement of a DUT-49 sample bed filmed in a glass capillary during adsorption of _n_-butane at 298—299 K.
- [`supplementary video 2.wmv`](supplementary%20video%202.wmv): Visualization of the framework’s structural transition. This video clip illustrates in an animation the framework structural transition including visualization of ligand deformation and changes of pore size occurring upon contraction of DUT-49op to DUT-49cp.


**Results / data files:**

- [`DUT-49op-DFT.cif`](DUT-49op-DFT.cif): DFT-optimized structure of DUT-49op (open-pore structure).
- [`DUT-49cp-DFT.cif`](DUT-49cp-DFT.cif): DFT-optimized structure of DUT-49cp (contracted-pore structure).


**Input files:**

Software used is [CRYSTAL14](http://www.crystal.unito.it/), version 1.0.2, massively parallel distributed data version (MPPcrystal) on PowerPC  64-bit GNU/Linux system (IBM Blue Gene/Q machine [Turing](http://www.idris.fr/eng/turing/turing-presentation-eng.html) at [IDRIS](http://www.idris.fr/eng/)).

- [`DUT-49op-optcell.d12`](DUT-49op-optcell.d12): input file for full cell optimization of DUT-49op structure.
- [`DUT-49op-elastic.d12`](DUT-49op-elastic.d12): input file for calculation of the elastic tensor of DUT-49op.
- [`DUT-49cp-optatom.d12`](DUT-49cp-optatom.d12): input file for atomic positions optimization of DUT-49cp structure.


**Elastic constants of DUT-49op**

From a direct calculation of the elastic tensor of DUT-49op, we find the following well-converged elastic constants: _C_<sub>11</sub> = 13.0 GPa, _C_<sub>12</sub> = 6.6 GPa.

_C_<sub>44</sub> is more difficult to evaluate, and the value obtained is very sensitive to amount of strain (_δε_) applied, demonstrating a strong nonlinearity of the elastic behavior for DUT-49op. The best estimate is obtained from _δε_ = –0.01, which gives _C_<sub>44</sub> = 1.5 GPa.
