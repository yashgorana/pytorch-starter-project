# PyTorch Starter Project

A start project for PyTorch 2.0 with GPU support (CUDA 11.7).

Includes the following libraries for typical ML projects

| Package                    | Description                             |
|----------------------------|-----------------------------------------|
| `timm`, `transformers`     | Pre-built SOTA models for PyTorch       |
| `matplotlib`, `seaborn`    | For visualizing your data               |
| `requests`                 | Working with HTTP APIs                  |
| `click`                    | Building CLI apps                       |
| `mlflow`                   | E2E ML lifecycle management             |
| `black`, `flake8`, `isort` | Code format & linting                   |

## Requirements

Currently supports Conda/Miniconda/Mamba running on Linux & Windows

## Setup

First setup a Python 3.10 + Pytorch 2.0 environment using conda

    $ pip install conda-lock
    $ conda-lock install -p .venv

Then install additional python packages inside this environment

    $ conda activate .venv/
    $ poetry install

## License

The source code for the site is licensed under the MIT license, which you can find in the [LICENSE](./LICENSE) file.
