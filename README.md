# SMAP
https://softwaredefinedbuildings.github.io/smap/

## Getting Started

### Installation

#### Python

To setup a clean environment, create a new python virtual environment with:

    virtualenv venv

Before proceeding with installation, make sure you've sourced the virtual environment with `source venv/bin/activate`.

You must install the dependencies listed in one of the `requirements.txt` files before installing smap. Do this by issuing one of the following:

    pip install -r python/requirements.txt
    pip install -r python/osx_requirements.txt

After the dependencies are installed, run the installation:

    python setup.py install

## Build status 
[![Build Status](https://travis-ci.org/SoftwareDefinedBuildings/smap.svg?branch=master)](https://travis-ci.org/SoftwareDefinedBuildings/smap)
