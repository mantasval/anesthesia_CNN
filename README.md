# EEG Classification for Anesthesia Depth Using CNNs

This repository contains the code and resources used for the analysis and results presented in the thesis **"Classification of Anesthesia Depth Based on Raw Electroencephalogram Signals Using Convolutional Neural Networks"**.

## Project Overview

The project aims to classify anesthesia depth using convolutional neural networks (CNNs) trained on raw electroencephalogram (EEG) signals. The classification tasks include:
- Multiclass classification (all-vs-all)
- Binary one-vs-all classification
- Binary one-vs-one classification

## Directory Structure

- **`all_vs_all.ipynb`**: Code for the all-vs-all classification task. Results used in the thesis are further processed in `results.ipynb`.
- **`models/`**: Contains saved models as `.keras` files.
- **`training_data/`**: Directory for processed training data.
- **`data/`**: Contains the initial raw data files (`.mat` format).
- **`oVo/`**: Directory for one-vs-one and one-vs-all classification.

### Supporting Files and Directories
- **`results.ipynb`**: Processes and visualizes results from all-vs-all classification.
- **`CMs/`**: Contains confusion matrices (`.csv` and `.png`) for all tasks.
- **`CM_figs_norm/`**: Normalized confusion matrices as images.
- **`final_figs/`**: Final figures used in the thesis.

## Usage

1. **Run all-vs-all Classification**:
   - Use `all_vs_all.ipynb` to train and evaluate the multiclass model.
   - Process and visualize results using `results.ipynb`.

2. **Run one-vs-all and one-vs-one Classification**:
   - Use `oVo/ovo.ipynb` to train and evaluate models for these tasks. Results and performance metrics are saved in the same notebook.

3. **Access Saved Models**:
   - Saved models are stored in the `models/` directory.

4. **Data**:
   - Raw data (`.mat` files) is stored in `data/`.

## Thesis Reference

This repository is directly associated with the thesis **"Classification of Anesthesia Depth Based on Raw Electroencephalogram Signals Using Convolutional Neural Networks"** by Mantas Valiulis (Vilnius University, 2025).
