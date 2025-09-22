# MCAS-vascular-aging

This repository hosts the code and processed data associated with the manuscript:

**"Microbial Cardiovascular Aging Signature (MCAS): A Multi-Omics Integrative Framework"**

---

## Repository Structure

- `code/`  
  Contains analysis scripts used for PCA integration, predictive modeling, and risk stratification.  
  - `Supplementary_Code_MCAS.txt`

- `data/`  
  Processed multi-omics datasets and model outputs used in the study.  
  - `Supplementary_Data1.csv`  
  - `Supplementary_Data2.csv`  
  - `Supplementary_Data3.txt` (includes both `integrated_matrix.csv` and `labels.csv`)  
  - `integrated_matrix.csv`  
  - `labels.csv`  
  - `Supplementary_Data4.json`  
  - `Supplementary_Data5.json`

- `results/`  
  Example figures and outputs (to be added if needed).

---

## How to Reproduce Analyses

1. Clone this repository:
   ```bash
   git clone https://github.com/erkanozbay-biophysics/kmu-lab-MCAS-vascular-aging.git
   cd kmu-lab-MCAS-vascular-aging
   ```

2. Run the analysis script:
   ```bash
   python code/Supplementary_Code_MCAS.txt
   ```

   If you prefer, rename the script to `.py` before running:
   ```bash
   mv code/Supplementary_Code_MCAS.txt code/Supplementary_Code_MCAS.py
   python code/Supplementary_Code_MCAS.py
   ```

3. Input data are located in `data/`, and output results will be saved in `results/`.

---

## License

This project is licensed under the MIT License.
