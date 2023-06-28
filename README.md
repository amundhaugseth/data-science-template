# Micromamba Dev Container for Data Science

This repository provides a GitHub template for a Python data science development environment using Micromamba, a small and fast Conda environment manager. The environment is containerized using Docker and configured for use with Visual Studio Code's [Development Containers](https://code.visualstudio.com/docs/devcontainers/containers)

## Project Structure

- `.devcontainer/`:
  - `dev-conda-environment.yaml`: This file specifies the Python environment for the development container.
    - `dev.Dockerfile`: This file contains the instructions for building the development container.
    - `devcontainer.json`: This file contains the configuration for the development container.
- `data/`: This directory contains data.
  - `processed/`: This directory contains processed data.
  - `raw/`: This directory contains raw data.
  - `temp/`: This directory contains temporary data.
  - `training/`: This directory contains training data.
- `docs/`: This directory contains documentation.
- `models/`: This directory contains trained models.
- `notebooks/`: This directory contains Jupyter notebooks.
- `reports/`: This directory contains reports.
  - `figures/`: This directory contains figures.
- `src/`: This directory contains the source code.
- `tests/`: This directory contains tests.
- `README.md`: This file contains the documentation.

## Usage

### Requirements

To run this project, you will need:

- [Docker](https://www.docker.com/get-started)
- [Visual Studio Code](https://code.visualstudio.com/download)
- [Dev Containers extension for VSCode](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

Then you can clone this repository, open the cloned directory in VS Code, and use the "Remote-Containers: Open Folder in Container" command from the Command Palette (F1) to build and start the development container.

Once inside the container, you'll have access to a comprehensive data science environment, with useful VS Code extensions already installed and configured.
