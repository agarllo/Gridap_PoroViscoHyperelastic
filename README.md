# Gridap_PoroViscoHyperelastic
This repository contains the Julia code implementations described in the article [A Gridap-based Poro-Visco-Hyperelastic model implementation in
Julia: Application to cartilage](https://www.sciencedirect.com/science/article/pii/S0169260725002925) UPDATE LINK. The scripts correspond to the becnhmarks presented in the paper, enabling full reproducibility of the reported results.

- **BENCHMARK 1: Terzaghi’s consolidation problem.** Terzaghi’s consolidation problem describes the time-dependent dissipation of excess pore pressure in a saturated porous medium subjected to a sudden load. It models the coupled interaction between fluid flow and soil deformation, governed by the theory of one-dimensional consolidation. This benchmark is widely used to validate numerical formulations for poroelasticity.
  <img width="1280" height="720" alt="Image" src="https://github.com/user-attachments/assets/d3e2c099-b51e-4fb4-819c-bdb92c72de78" />
- **BENCHMARK 2: Partially loaded 2D plate.** The partially loaded 2D plate benchmark models a poroelastic material subjected to a localized surface load, allowing the study of coupled solid deformation and fluid flow. It is commonly used to validate numerical implementations of poroelasticity under non-uniform loading conditions.
- https://github.com/user-attachments/assets/947825a9-d83e-4ab2-8c54-7d2114572c43
- **BENCHMARK 3: Cartilage permeability test.** Cartilage exhibits poro-visco-hyperelastic behavior, where a nonlinear elastic matrix (Neo-Hookean), viscoelasticity (Kelvin-Voigt model), and interstitial fluid flow (Darcy's law)  govern its behavior. Fluid flow through the porous network contributes governs the time-dependent mechanical response, particularly under confined or compressive conditions.

## Citation
If you find our work to be useful for your research, please cite [our paper](https://arxiv.org/abs/2401.12974):

```bibtex
@misc{GarciaLlona2026,
      title={A Gridap-based Poro-Visco-Hyperelastic model implementation in Julia: Application to cartilage.}, 
      author={Aratz Garcia-Llona, Victor Acosta, Francesc Verdugo, Miquel Aguirre and Stéphane Avril},
      year={2026},
      eprint={2401.12974},
      archivePrefix={arXiv},
      primaryClass={eess.IV}
```
}
