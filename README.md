# convex-env
*Anders Poirel*

Python environment for convex optimization.

## Requirements

- `conda` (I recommend using [miniconda](https://docs.conda.io/en/latest/miniconda.html))

## Usage

Clone this repository. In this directory, install the environment
```sh
conda env create -f environment.yml
```
Activate the environment
```sh
conda activate cvxpy
```
In Jupyter Lab, the correct notebook kernel will likely not appear by default. To solve this, use
```sh
python -m ipykernel install --user --name cvxpy
```
To run a notebook in this environment, use
```sh
jupyter lab
```
And then 

## License

This repository is license under the [MIT License](https://github.com/Jswig/convex-env/blob/main/LICENSE)
