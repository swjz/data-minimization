# Algorithmic Data Minimization for Machine Learning over IoT Data Streams

## Overview
This repository contains the supplemental materials for our paper, including the code and processed evaluation figures used in the experiments. Each dataset used in the paper has its own dedicated folder containing Jupyter notebooks to reproduce the results. The `figures` folder contains all evaluation figures used in the paper.

## Repository Structure
```
├── README.md  # This file
├── figures/   # Contains all processed evaluation figures used in the paper
├── cic-ids2017/  # Code to reproduce results on the CIC-IDS2017 dataset
│   ├── baselines.ipynb
│   ├── exhaustive.ipynb
│   └── hypermapper.ipynb
├── device-ident-nprint/  # Code to reproduce results on the device identification dataset using nPrint
│   ├── baselines-iot_nprint_3pkts-aligned-nprint.ipynb
│   ├── exhaustive.ipynb
│   └── hypermapper.ipynb
├── device-idnet-netml/  # Code for device identification using NetML
│   ├── baselines-iot_nprint_3pkts-stats.ipynb
│   ├── exhaustive.ipynb
│   └── hypermapper.ipynb
├── iot-23/  # Code for IoT-23 dataset
│   ├── exhaustive.ipynb
│   └── hypermapper.ipynb
├── iot-sentinel/  # Code for IoT Sentinel dataset
│   ├── baselines.ipynb
│   ├── exhaustive.ipynb
│   └── hypermapper.ipynb
├── opportunity/  # Code for Opportunity dataset
│   ├── baselines.ipynb
│   ├── exhaustive.ipynb
│   └── hypermapper.ipynb
├── service-recognition-nprint/  # Code for service recognition dataset using nPrint
│   ├── baselines-serv_rec_full_nprint_10pkts-parallel.ipynb
│   ├── brute-force-utility-score-serv_rec_full_nprint_10pkts.ipynb
│   └── hypermapper-serv_rec_full_nprint_10pkts-utility-score.ipynb
```

## Description of Contents
### Code Directories
Each directory corresponds to a dataset used in the paper. Within each directory, the following Jupyter notebooks are included:
- `baselines.ipynb`: Implements baseline models for comparison between selection methods.
- `hypermapper.ipynb`: Utilizes HyperMapper to conduct exhaustive search.
- `exhaustive.ipynb`: Performs filtering after getting the results from exhaustive search.

(Note: Some directories may have slight variations in notebook names due to dataset-specific implementations.)

### Figures
The `figures/` directory contains pre-generated evaluation plots used in the paper. These figures are categorized based on dataset and type of analysis.

## Contact
For any questions regarding the repository, please contact the authors of the paper.


