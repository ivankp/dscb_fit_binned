# Setting up python environment

``` Python
mkdir python
cd python
python -m venv .
source bin/activate
pip install --upgrade pip
pip install numpy matplotlib notebook 'jax[cpu]'
```

# Running notebooks

``` Python
source python/bin/activate
cd notebooks
jupyter notebook
```
