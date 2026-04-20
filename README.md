# Shell Acoustic Imperfection

This repository contains digital materials associated with the manuscript:

> Krida, I., Tang, J., Mangalath, L., Floryan, D., Chen, T. (2026). 
> Vibration-Assisted Fabrication of Thin Shells with Spatially Distributed Imperfections. 
> *Nature Communications*, in press.

It is intended to support transparency, reproducibility, and data availability 
for the results presented in the manuscript.

## Repository Contents

- **`data/`** — Plot-ready experimental data used to generate the figures.
- **`scripts/`** — Python scripts that reproduce each figure from the data files.
- **`manuscript/`** — LaTeX source for the main manuscript and Supplementary Information.

## Figure-to-Script Mapping

| Manuscript Figure | Data                          | Script                    |
|-------------------|-------------------------------|---------------------------|
| Fig. 3d           | `data/CSVs/thickness-plotting-*.csv`    | `plotting/thickness-plotting.ipynb`  |
| Fig. 4c           | `data/CSVs/exp_fem_corr_*.csv`   | `scripts/exp_fem_correlation.ipynb`  |
| Fig. 4e           | `data/CSVs/thickness_azimuthal_profiles.csv`   | `scripts/thickness-comparison.ipynb`  |
| Fig. 5            | `data/CSVs/PV_*.csv`     | `scripts/PV_{06,08,10}_plot.ipynb` |

## Requirements

Scripts are developed and tested with Python 3.10+ and the following packages:
NumPy, pandas, SciPy, and Matplotlib.

Install with:

```
pip install numpy pandas scipy matplotlib
```

## License

Code is released under the MIT License. Data is released under CC-BY 4.0 
and may be reused with attribution to the manuscript cited above.

## Contact

For questions, please contact the corresponding author at tian.chen@uh.edu.