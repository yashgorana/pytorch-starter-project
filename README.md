# PyTorch Starter Project

A start project for PyTorch 2.0 with GPU support (CUDA 11.7).

Includes the following libraries for typical ML projects

| Package                    | Description                             |
|----------------------------|-----------------------------------------|
| `timm`, 'transformers'     | Pre-built SOTA image models for PyTorch |
| `numpy`                    | Numerical compute                       |
| `pandas`                   | Working with datasets                   |
| `matplotlib`, `seaborn`    | Build visualisations                    |
| `requests`                 | Working with HTTP APIs                  |
| `click`                    | building CLI apps                       |
| `mlflow`                   | E2E ML lifecycle management             |
| `black`, `flake8`, `isort` | Code format & linting                   |

## Requirements

This project is tested to work on Linux, Windows and WSL2. Python version requirement follows PyTorch requirement for each platform.

Currently supports: Python 3.8 to 3.11

## Setup

Run the following to install poetry

    $ pip install --upgrade poetry

Then run the following to install the dependencies

    $ poetry install

To add a new dependency, just run

    $ poetry add <package_name>


## License

The source code for the site is licensed under the MIT license, which you can find in the [LICENSE](./LICENSE) file.
