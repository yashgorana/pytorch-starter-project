# PyTorch Starter Project

A start project for PyTorch 1.13 with GPU support (CUDA 11.6).

Includes the following libraries for typical ML projects

| Package                    | Description                             |
|----------------------------|-----------------------------------------|
| `timm`                     | Pre-built SOTA image models FOR PyTorch |
| `numpy`                    | Numerical compute                       |
| `pandas`                   | Working with datasets                   |
| `matplotlib`, `seaborn`    | Build visualisations                    |
| `requests`                 | Working with HTTP APIs                  |
| `click`                    | building CLI apps                       |
| `mlflow`                   | E2E ML lifecycle management             |
| `black`, `flake8`, `isort` | Code format & linting                   |

## Requirements

This project is tested to work on Linux, Windows and WSL2. Python version requirement follows PyTorch requirement for each platform.

Currently supports: Python `3.8`, `3.9`

## Setup

Run the following to install poetry

    $ pip install --upgrade poetry

Then run the following to install the dependencies

    $ poetry install

To add a new dependency, just run

    $ poetry add <package_name>


## License

The source code for the site is licensed under the MIT license, which you can find in the [LICENSE](./LICENSE) file.
