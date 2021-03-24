# Vlasov 

This project provides some Vlasov solvers written in Python. 

## Contents

[1. Landau Damping](https://nbviewer.jupyter.org/github/ratnania/vlasov/blob/main/notebooks/LandauDamping.ipynb)

[2. Bump on Tail](https://nbviewer.jupyter.org/github/ratnania/vlasov/blob/main/notebooks/BumpOnTail.ipynb)

[3. Vlasov Maxwell 1d1v](https://nbviewer.jupyter.org/github/ratnania/vlasov/blob/main/notebooks/VlasovMaxwell1D1V.ipynb)

## How to use this material

### Using a virtual environement (recommanded)

First you need to create a virtual environement:

```shell
python3 -m venv .vlasov
```

you activate this environement using

```shell
source .vlasov/bin/activate
```

Then install dependencies using

```shell
pip3 install -r requirements.txt
```

Adding the virtual environement to Jupyter notebook, can be done using

```shell
python3 -m ipykernel install --user --name=.vlasov
```

### without virtual environement

Install dependencies using

```shell
pip3 install -r requirements.txt
```

