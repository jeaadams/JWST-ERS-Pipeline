# JWST-ERS-Pipeline

[![Powered by AstroPy](https://img.shields.io/badge/powered_by-AstroPy-EB5368.svg?style=flat)](http://www.astropy.org)
[![Powered by pyKLIP](https://img.shields.io/badge/powered_by-pyKLIP-EB5368.svg?style=flat)](https://bitbucket.org/pyKLIP/pyklip/src/master/)


Tutorials to aid in understanding simulated data from the James Webb Space Telescope and estimate its performance imaging exoplanets.


## Installation

The functions utilized in this notebook require Python version 3.8.5 or above.

To use these notebooks in your global environment, you'll need to install the packages in our requirements.txt. You can do this by running the following:

```bash
pip install -rf requirements.txt
```

### OR 

Run in a virtual environment using pipenv. This will ensure that your dependency graph is compatible.


```bash
pip3 install pipenv
git clone https://github.com/jeaadams/JWST-ERS-Pipeline.git
cd Jwst_ERS_Pipeline
python3 -m pipenv shell
```

Alternatively, if you're on MacOS, you can install pipenv using Homebrew: 

```bash
brew install pipenv
git clone https://github.com/jeaadams/JWST-ERS-Pipeline.git
cd Jwst_ERS_Pipeline
pipenv shell
```
