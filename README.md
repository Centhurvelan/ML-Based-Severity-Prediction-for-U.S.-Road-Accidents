# ML-Based-Severity-Prediction-for-U.S.-Road-Accidents

DS PROJECT — ML-Based Severity Prediction for U.S. Road Accidents

## Overview
This repository contains Jupyter notebooks and starter project files for predicting accident severity using U.S. road-accident data. The notebooks include exploratory data analysis, preprocessing, model training, and evaluation.

## Quickstart
1. Clone the repository:
   ```bash
   git clone https://github.com/Centhurvelan/ML-Based-Severity-Prediction-for-U.S.-Road-Accidents.git
   cd ML-Based-Severity-Prediction-for-U.S.-Road-Accidents
   ```
2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # macOS/Linux
   .\.venv\Scripts\activate   # Windows
   pip install -r requirements.txt
   ```
3. Place datasets in the `data/` directory (see Data section below).
4. Open notebooks:
   ```bash
   jupyter lab
   ```

## Project structure
- `notebooks/`: Jupyter notebooks (existing)
- `src/`: Python package (recommended for refactor)
- `data/`: raw and processed data (gitignored)
- `models/`: trained model artifacts (gitignored)
- `tests/`: unit tests

## Data
Do not commit raw datasets. Add data files to `data/raw/` or follow the download instructions included in the notebooks.

## Contributing
If you'd like the notebooks refactored into reusable modules, tests added, and CI configured to run them, ask for option B and I will proceed.

## License
This project is licensed under the MIT License — see `LICENSE`.