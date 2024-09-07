# Data Analysis for Materials Science

This repository contains data and analyses related to **Materials Science**. It includes diffraction results and spectrum analysis for various materials, showcasing the use of Python for data manipulation and visualization.

## Table of Contents

1. [Introduction](#introduction)
2. [Diffraction Results](#diffraction-results)
3. [Spectrum Analysis](#spectrum-analysis)
4. [Files in the Repository](#files-in-the-repository)
5. [Getting Started](#getting-started)
6. [Installation](#installation)
7. [Contributing](#contributing)
8. [License](#license)

---

## Introduction

This repository presents an analysis of materials science data, specifically focusing on **diffraction results** and **spectrum analysis**. Using Python and associated libraries, such as NumPy and Matplotlib, the data is processed to draw insights into the structure and properties of various materials.

By the end of this repository, you will have explored:
- Diffraction data results showing mean values for materials analysis.
- Spectral analysis for multiple materials with different d-spacing values.
- A step-by-step Python-based workflow for analyzing diffraction and spectrum data.

## Diffraction Results

The diffraction data includes mean values and standard deviations for different data points, useful for analyzing material structures at an atomic level. The `diffraction_results.txt` file contains processed results showing variations in materials' diffraction patterns.

Example structure of diffraction data:
```
Mean Value: 5.8
Standard Deviation: 0.2
```

You can explore the full file here: [diffraction_results.txt](./diffraction_results.txt).

## Spectrum Analysis

The spectrum data files provide insights into the intensity counts at various d-spacing values. Each spectrum file corresponds to different measurements and materials. Below is a summary of some of the spectrum files:

- **spectrum_1.txt**: Initial spectrum data with very low counts and some peaks.
- **spectrum_10.txt** and **spectrum_10_2Ang.txt**: Spectrum data at 10° with higher counts for intensity.
- **spectrum_30.txt** and **spectrum_30_2Ang.txt**: Data for spectrum analysis at 30°, showing higher intensity at specific d-spacing values.

Example from `spectrum_1.txt`:
```
d-spacing    Intensity (counts)
0.629774     7182.42
0.635733     7160.19
```
Explore the file here: [spectrum_1.txt](./spectrum_1.txt).

## Files in the Repository

- **`diffraction_results.txt`**: Contains diffraction results for analysis.
- **`output.txt`**: Contains mean values and data for various samples.
- **Spectrum Files**:
  - `spectrum_1.txt`
  - `spectrum_1_2Ang.txt`
  - `spectrum_10.txt`
  - `spectrum_10_2Ang.txt`
  - `spectrum_20.txt`
  - `spectrum_20_2Ang.txt`
  - `spectrum_30.txt`
  - `spectrum_30_2Ang.txt`

Each spectrum file includes intensity counts for different materials and conditions.

## Getting Started

### Prerequisites

To analyze and visualize the data, you will need:

- Python 3.x
- NumPy for data manipulation
- Matplotlib for visualizing the spectrum data
- Jupyter Notebook (optional, for interactive analysis)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/smahala02/Materials-Science-Data-Analysis.git
   ```

2. Install the required Python packages:

   ```bash
   pip install numpy matplotlib
   ```

3. (Optional) Open the Jupyter notebook for interactive analysis:

   ```bash
   jupyter notebook 'Data Analysis for Materials Science.ipynb'
   ```

## Contributing

Contributions are welcome! If you have suggestions or would like to add more data analysis scripts, feel free to submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b new-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin new-feature`).
5. Open a pull request.

## License

This repository is licensed under the MIT License. See the `LICENSE` file for more details.

## Author
- [smahala02](https://github.com/smahala02)

