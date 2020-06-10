# Distributions

Example of a Python Package implementing Gaussian and Binomial Distributions

## Install from Local

```
# First time install
pip install .

# Subsequent installs
pip install --upgrade .
```

## Upload to PyPI

```
python setup.py sdist
pip install twine

# commands to upload to the pypi test repository
twine upload --repository-url https://test.pypi.org/legacy/ dist/*
pip install --index-url https://test.pypi.org/simple/ dsnd-probability

# command to upload to the pypi repository
twine upload dist/*
pip install dsnd-probability
```
