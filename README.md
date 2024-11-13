This project uses image analysis techniques to analyze the effects of phosphorus fertilization and a phosphorus absorption enhancer on tomato plants.

## Project Overview

Tomato plants were subjected to three treatments:
1. Control (no phosphorus fertilization)
2. Standard phosphorus fertilization
3. Phosphorus fertilization + absorption enhancer

Images of the plants were processed to isolate leaf data, which was then analyzed using texture and color indices. Statistical tests (ANOVA and Tukey) were performed to compare the effects of different treatments.

## Key Findings

The study found significant differences in leaf quantity, texture, and color when the phosphorus absorption enhancer was used, indicating its effectiveness in improving plant phosphorus uptake.

## Repository Structure

- `data/`: processed data files
- `Phosphorous_Analysis.ipynb`: Jupyter notebook with data analysis code
- - `results/`: Output files from statistical analyses
- `figures/`: Generated plots and visualizations
- `requirements.txt`: List of Python dependencies

## Setup and Usage

1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebooks in the `notebook/` directory to reproduce the analysis

## License

This project is licensed under the MIT License - see the LICENSE file for details.
