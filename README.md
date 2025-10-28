# Globular Cluster Mass Estimation (MASS-GC)

This repository contains code and data for estimating the mass of a globular cluster using surface brightness profile analysis and tidal radius determination.

## Overview

The experiment focuses on determining the mass of globular clusters through analysis of their surface brightness profiles. The method is based on the theoretical framework where the tidal radius of a cluster is determined by balancing the gravitational forces between the cluster and its host galaxy.

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### What you can do with this code:
- ✅ Use freely for personal, academic, or commercial projects
- ✅ Modify and adapt the code
- ✅ Distribute the code
- ✅ Use in proprietary software
- ✅ Use for teaching and research purposes

### Requirements:
- ❗ You must include the original copyright notice and license in any copy
- ❗ No warranty or liability provided - use at your own risk

### For Academic Users:
If you use this code in academic research, please consider citing the original work by Prof. Johan van der Walt and Prof. Christo Venter.

## Key Features

- **Surface Brightness Profile Calculation**: Converts cumulative flux measurements to surface brightness profiles
- **Tidal Radius Estimation**: Automatically estimates tidal radius from surface brightness data
- **Unit Conversion**: Handles conversion between angular measurements (arcminutes) and physical distances (parsecs)
- **Data Visualization**: Provides comparative plots of normalized flux and surface brightness profiles

## Theoretical Background

The mass of a globular cluster is estimated using the formula:

m = 3.5M(R_t/d)^3

Where:
- m = mass of the globular cluster
- M = mass of the host galaxy (Milky Way)
- R_t = tidal radius of the cluster
- d = distance from cluster to galactic center

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib

## Installation

```bash
git clone https://github.com/yourusername/globular-cluster-mass-estimation.git
cd globular-cluster-mass-estimation
pip install numpy pandas matplotlib openpyxl
