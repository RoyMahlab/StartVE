# Environment Setup for This Repository

This repository holds a single main file, designed to help you set up the necessary environment packages. The environment will be built using the following specifications:

## Environment Details

- **Python**: 3.10.2
- **PyTorch**: 2.4.1
- **Torchvision**: 0.19.1
- **Torchaudio**: 2.4.1
- **CUDA Version**: 12.1
- **NumPy**: 1.26.4
- **SciPy**: 1.13.1
- **Torch-Geometric**: 2.6.1
- **IPython**: 8.28.0
- **Pip**: 24.2

## Installation Instructions

To set up the environment, run the provided file (e.g., `install_env.sh` or `environment.yml`) which will install the specified packages. If additional packages are needed, please install them manually.

Feel free to modify or add any other dependencies as required.

```bash
wget https://github.com/RoyMahlab/StartVE/tree/main/environment.yaml | conda env create -f environment.yaml
