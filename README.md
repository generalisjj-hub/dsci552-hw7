# DSCI 552 Homework 7

Open `notebook/Jiang_Jun_HW7.ipynb` for the answers, code, and saved outputs. The original Anuran Calls data is in `data/`.

With Python 3.12, run from the repository root:

```sh
uv sync --frozen
uv run jupyter nbconvert --to notebook --execute --inplace notebook/Jiang_Jun_HW7.ipynb --ExecutePreprocessor.timeout=3600
```

Alternatively, install `requirements.txt` into a Python 3.12 environment. The full cross-validation and 50-run clustering may take several minutes.

The complete printable PDF is `output/pdf/Jiang_Jun_HW7.pdf` (5 US Letter pages).
