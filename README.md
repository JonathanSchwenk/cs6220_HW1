# CS 6220 HW1 – Iris pipeline

## Setup
```
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```
Open `homework_1.ipynb` and choose Run > Run All Cells.

The notebook loads `iris.data` (UCI) from the project folder, otherwise downloads it from UCI,
otherwise falls back to scikit-learn's bundled copy.
