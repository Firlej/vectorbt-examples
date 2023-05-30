# vectorbt-examples

Example usage for [vectorbt](https://github.com/polakowo/vectorbt) library for backtesting. Notebooks saved in this repository are to log my learning process.

This is not clean code, but rather a collection of code snippets that I found helpful.

[vectorbt documentation](https://vectorbt.dev/)

[https://github.com/TA-Lib/ta-lib-python](https://github.com/TA-Lib/ta-lib-python)

## Init

Create and activate conda env (`vectorbt` doesn't support pyton 3.11 at this point in time)
```bash
conda create --name vectorbt python=3.10
conda activate vectorbt
```

#### Install requirements
```bash
pip install -r requirements.txt
```

### Helpful commands

```bash
pip install ipykernel numpy pandas ccxt tqdm vectorbt nbformat
pip freeze > requirements.txt
```
