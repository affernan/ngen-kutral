# Ngen Kutral

Ngen Kutral is an open-source Python framework for wildfire spread simulation, with experiments focused on Chilean wildfire scenarios.

This repository is a fork of the original project by Daniel San Martin and Claudio E. Torres. It includes the framework source code and experiment scripts associated with the work "Ngen Kutral: Toward an Open Source Framework for Chilean Wildfire Spreading".

## Repository Structure

- `wildfire/`: Core simulation modules.
- `experiments/`: Example simulations and experiment scripts.
- `experiments/JCC2018/`: Scripts used for the JCC 2018 experiments.
- `LICENSE`: Project license.

## Requirements

The original project was developed with:

- Python 3.6.5 or later
- NumPy 1.13.3 or later
- SciPy 1.1.0 or later
- Matplotlib 2.2.2 or later

## Setup

Clone the repository and add the package root to `PYTHONPATH`:

```bash
export PYTHONPATH="$PYTHONPATH:/path/to/ngen-kutral"
```

## Running Experiments

From the repository root, run one of the experiment scripts:

```bash
python experiments/JCC2018/asensio_2002.py
```

Other scripts in `experiments/` and `experiments/JCC2018/` can be used as references for configuring simulations and generating plots.
