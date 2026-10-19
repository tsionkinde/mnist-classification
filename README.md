# Crop disease recognition

## Python environment

This project uses Python 3.10. Create the project environment and install the notebook dependencies with:

```bash
python3.10 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install numpy scikit-learn matplotlib ipykernel
python -m ipykernel install --user --name crop-disease --display-name "Python 3.10 (crop-disease)"
```

In Jupyter, select **Python 3.10 (crop-disease)** for `mnist_classification.ipynb`. To confirm the active interpreter in a cell:

```python
import sys
print(sys.version)
print(sys.executable)
```

The interpreter path should end in `.venv/bin/python` and the version should start with `3.10`.
