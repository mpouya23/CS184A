# CS184A/284A Final Project – Protein Function Prediction for CAFA-6

**Student:** Melina Pouya  
**Course:** CS 184A/284A – Fall 2025  

This repository contains the code and demo data for my final project on
protein function prediction using deep learning and ESM2 embeddings.

---

## Contents

- `project.zip`  
  - Compressed project folder used for submission.
  - Inside `project.zip` there is a `project/` directory with:
    - `project.ipynb` – demo notebook (runs in < 1 minute)
    - `project.html` – HTML export of the notebook
    - `README.txt` – detailed description of all files in `project/`
    - `data/sample_data.npz` – small sample of precomputed ESM2 embeddings
    - `src/` – helper Python modules (data loading, model, training, prediction)
      
---

## How to use

1. Download `FinalProject.zip` from this repository.
2. Unzip it to get the `project/` folder.
3. Open `project/project.ipynb` in Jupyter, VS Code, or Google Colab.
4. Run all cells from top to bottom to:
   - load the sample dataset,
   - train a small neural network on ESM2 embeddings,
   - compute micro-F1 on a validation split,
   - inspect example GO term predictions for one protein.

For more details about file structure and dependencies, see
`project/README.txt` inside the unzipped folder.
