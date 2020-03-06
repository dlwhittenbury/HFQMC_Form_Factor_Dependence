# Form Factor Dependence in Guichon _et al_'s Hartree-Fock QMC Model

This is a Mathematica notebook containing calculations and some rough notes on
the Hartree-Fock Quark-Meson Coupling model (HF-QMC) model as it appears in
[Nucl. Phys. A772, 1-19 (2006)](https://www.sciencedirect.com/science/article/abs/pii/S0375947406001539?via%3Dihub)
and [Nucl. Phys. A792, 341-369 (2007)](https://www.sciencedirect.com/science/article/abs/pii/S037594740700574X), but minimally extended to include a dipole form factor in the Fock terms.

Hartree-Fock QMC model calculations performed here use simpler Fock terms than what was included in [my PhD thesis](https://inspirehep.net/record/1495499/files/02whole.pdf). The most notable difference is that it does not include the tensor contributions of the vector mesons. Moreover, this notebook only calculates properties of Symmetric Nuclear Matter (SNM).

The aim of this notebook was just to quickly see the EoS dependence on the various contributions and approximations. Throughout default options were mostly used and so the calculation could be improved to be more precise and general, which will likely slow the notebook considerably. A more complete calculation should rather be done in another language such as Fortran, C or C++. However, this should still be useful for understanding how such a calculation can be done and the various contributions to the EoS. Here we have focussed on SNM and in particular the simplified Fock terms. We investigate the various contributions to the energy density, the incompressibility and the slope of the symmetry energy. In particular this notebook can calculate:

- Energy Density

- Binding Energy

- Pressure

- Incompressibility

- Symmetry Energy (Two methods difference and numerical finite difference formulas)

- Slope of the Symmetry Energy (using either method)

- Fit couplings and find saturation properties

- Create EoS table

- Create figures and tables for a few model variations

and does so for several model variations.


## References

1. [Nucl. Phys. A772, 1-19 (2006)](https://www.sciencedirect.com/science/article/abs/pii/S0375947406001539?via%3Dihub) P. A. M. Guichon, H. H. Matevosyan, N. Sandulescu and A. W. Thomas, Physical origin of density dependent forces of Skyrme type within the quark meson coupling model.

2. [Nucl. Phys. A792, 341-369 (2007)](https://www.sciencedirect.com/science/article/abs/pii/S037594740700574X) J. Rikovska-Stone, P. A. M. Guichon, H. H. Matevosyan and  A. W. Thomas, Cold uniform matter and neutron stars in the quark–meson-coupling model.

3. [D. L. Whittenbury, PhD thesis](https://inspirehep.net/record/1495499/files/02whole.pdf) Hadrons and Quarks in Dense Matter: From Nuclear Matter to Neutron Stars, University of Adelaide.


**See these references for a detailed list of references pertaining to theory, experiment and other data.**
