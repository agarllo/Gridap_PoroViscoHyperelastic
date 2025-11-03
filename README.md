# Gridap_PoroViscoHyperelastic
This repository contains the Julia code implementations described in the article [_A Gridap-based Poro-Visco-Hyperelastic model implementation in
Julia: Application to cartilage_](https://arxiv.org/abs/2401.12974). The scripts correspond to the becnhmarks presented in the paper, enabling full reproducibility of the reported results.

We update the codes to fine-tune the SegmentAnyBone to custom datasets, and the dataset preparation guideline can be found in our other repo: ![finetume-sam](https://github.com/mazurowski-lab/finetune-SAM/tree/main).
- BENCHMARK 1: Terzaghi’s consolidation problem.
- BENCHMARK 2: Partially loaded 2D plate.
- BENCHMARK 2: Cartilage permeability test.

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
