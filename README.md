# Shell Acoustic Imperfection

This repository contains digital materials associated with the manuscript:

> Krida, I., Tang, J., Mangalath, L., Floryan, D., Chen, T. (2026). 
> Vibration-Assisted Fabrication of Thin Shells with Spatially Distributed Imperfections. 
> *Nature Communications*, in press.

It is intended to support transparency, reproducibility, and data availability 
for the results presented in the manuscript and in the SI.

## Repository Contents

- **`data/`** — Plot-ready experimental data used to generate the figures.
- **`plotting/`** — Python scripts that reproduce each figure from the data files.
- **`manuscript/`** — LaTeX source for the main manuscript and Supplementary Information.

## Figure-to-Script Mapping

| Manuscript Figure | Data                                      | Script                                    |
|-------------------|-------------------------------------------|-------------------------------------------|
| Fig. 3d           | `data/thickness-plotting-08-*.csv`        | `plotting/thickness-plotting.ipynb`       |
| Fig. 4c           | `data/exp_fem_corr_*.csv`                 | `plotting/exp_fem_correlation.ipynb`      |
| Fig. 4e           | `data/thickness_azimuthal_profiles.csv`   | `plotting/thickness-comparison.ipynb`     |
| Fig. 5            | `data/PV_*.csv`                           | `plotting/PV_{06,08,10}_plot.ipynb`       |
| SI Fig. 1         | `data/stress-strain.csv`                  | `plotting/stress-strain.ipynb`            |
| SI Fig. 3         | `data/exp_correlation.csv`                | `plotting/exp_correlation.ipynb`          |
| SI Fig. 7         | `data/color_analysis_{H,S,V}.csv`         | `plotting/color_analysis.ipynb`           |
| SI Fig. 8         | `data/thickness-plotting-00-*.csv`        | `plotting/thickness-plotting-SI.ipynb`    |
| SI Fig. 10        | `data/exp_fem_corr_*.csv`                 | `plotting/exp_fem_correlation-full.ipynb` |
| SI Fig. 11        | `data/pressure-vol.csv`                   | `plotting/pressure-vol.ipynb`             |

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
