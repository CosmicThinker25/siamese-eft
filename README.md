# siamese-eft# Siamese Universes V — EFT Embeddings and DESI Constraints on Holographic Twin Cosmologies (v1.2)

This repository contains the LaTeX source, figures, and scripts for **Siamese Universes V**.  
**Paper PDF:** `siameseV.pdf`

## Abstract (short)
We implement a **toy EFT ansatz** as a multiplicative suppression applied to the CLASS linear matter power spectrum. The model alleviates the Hubble tension (~2σ), reduces σ8 by ~3%, and improves a light RSD χ² by +4.8 (~2.2σ over ΛCDM). It is falsifiable with Euclid and CMB-S4.

## Layout
- `siameseV.tex`, `siameseV.pdf` — main manuscript (v1.2)
- `figs/` — figures (PDF)
- `scripts/` — Python/Matplotlib scripts to regenerate figures
- `data/` — optional inputs/mocks

## Reproducibility
```bash
# regenerate example figures
python scripts/plot_contour_mock.py
python scripts/plot_fsigma8.py

# compile the paper
latexmk -pdf siameseV.tex
