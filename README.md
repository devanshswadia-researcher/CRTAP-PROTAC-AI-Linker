# CRTAP-PROTAC-AI-Linker
# AI-Driven PROTAC Linker Design for CRTAP Degradation

This repository contains the computational pipeline, screening framework, and generated candidate dataset for designing Proteolysis Targeting Chimeras (PROTACs) targeting the **CRTAP protein** using a **Thalidomide E3 Ligase Anchor**.

## Repository Contents
* `protac_generator.ipynb`: Google Colab / Jupyter Notebook containing the RDKit generative linker algorithm, QED screening filters, and 2D molecular visualization pipeline.
* `results.csv`: Complete dataset of generated viable PROTAC candidates, including canonical SMILES strings, Quantitative Estimate of Drug-likeness (QED) scores, and molecular weights.
* `requirements.txt`: Python package dependencies required to reproduce the environment.

## Quick Start (Google Colab)
1. Download `protac_generator.ipynb` from this repository.
2. Upload it to [Google Colab](https://google.com).
3. Run the installation cell (`!pip install rdkit deepchem openmm`) followed by the generation script.

## Local Installation
```bash
git clone https://github.com
cd CRTAP-PROTAC-AI-Linker
pip install -r requirements.txt
```

## Citation
If you use this pipeline or dataset in your research, please cite:
> [Swadia, Devansh.] (2026). *[CRTAP is an oncogenic driver of extracellular matrix stiffening in glioblastoma]*.

## License
Distributed under the MIT License. See `LICENSE` for details.
