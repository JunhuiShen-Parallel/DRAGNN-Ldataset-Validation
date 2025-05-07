# DRAGNN-Ldataset Validation

This repository contains the Ldataset files and DRAGNN code used in the paper:  
**Performance Evaluation of DRAGNN for Drug Repositioning on the Ldataset**

## Repository Structure
DRAGNN-Ldataset-Validation/
├── DRAGNN-main/ # Original DRAGNN code (unmodified)
│ └── ... # From https://github.com/1yiw/DRAGNN
├── data/ # Preprocessed Ldataset files
│ └── Ldataset/
│ ├── drug_sim.csv
│ ├── dis_sim.csv
│ └── drug_dis.csv
└── README.md # This document

## Usage
### 1. Get the Code
```bash
# Option 1: Use the included DRAGNN copy
cd DRAGNN-main

# Option 2: Fetch latest original code
git clone https://github.com/1yiw/DRAGNN

### 2. Run 10-fold Cross-Validation
cd DRAGNN-main
python main.py  --mode cv

Data Source:
Ldataset files preprocessed from https://github.com/xinliangSun/AdaDR/tree/main/AdaDR/raw_data/drug_data/Ldataset/lagcn

Contact
For questions regarding the implementation: js2ke@mtmail.mtsu.edu
