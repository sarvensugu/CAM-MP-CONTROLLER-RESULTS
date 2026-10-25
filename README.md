# CAM-MP Controller Results

This repository contains the SUMO simulation outputs and seed-level results supporting the study **CAM Based Max Pressure Controller for Urban Traffic Optimization**.

## Dataset

Download and extract `main_ten_seed_with_validation.zip` to access the results.

The dataset covers five traffic signal control models:

- Fixed-Time
- Acyclic Max Pressure (AMP)
- Cyclic Max Pressure (CMP)
- CAM-based Acyclic Max Pressure (CAM-AMP)
- CAM-based Cyclic Max Pressure (CAM-CMP)

Each model was evaluated using ten matched random seeds (40–49). Performance results cover the 0–3600 s evaluation period.

## Contents

- **Model folders** (`fixed`, `amp`, `cmp`, `cam_amp`, `cam_cmp`): outputs and run information organized by seed, including validation results where applicable.
- **Analysis folders**: seed-level metrics, summary tables, statistical comparisons and plots. The CSV tables are repeated across these folders; the folders provide alternative plot presentations.

The reported performance measures include average speed, waiting time, lane occupancy, time loss and queue length. Summary tables report means and sample standard deviations across the ten seeds.

## Notes

These results relate to the simulated network and experimental conditions described in the manuscript. Please refer to the manuscript for metric definitions, analysis methods and interpretation of the findings.

## Contact

For questions about the dataset, contact any of the author's listed in the manuscript.
