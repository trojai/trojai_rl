![alt-text-1](docs/source/images/TrojAI_logo.png "TrojAI Logo") ![alt-text-2](docs/source/images/apl2.png "APL Logo")

## Overview
This is the top-level TrojAI RL module.  It contains two submodules: `datagen` and `modelgen`. 
`datagen` contains the reinforcement learning (RL) environments used to generate trojaned models. The `modelgen` module contains the necessary API functions to generate DRL models from RL environments. 

## Getting Started
Check out our documentation here: <https://trojai.readthedocs.io>

This package is designed to be installed via `pip`, i.e. 

    pip install trojai_rl
    
or by cloning the repository and performing a local install (link may need to be updated):

    git clone https://github.com/trojai/trojai_rl.git
    cd trojai_rl
    pip install .
    
Note that the `gym` package may require some additional dependencies and support for Windows is still experimental. See: <https://github.com/openai/gym> for additional details.

## Repository Organization
```
trojai_rl
|   setup.py - Script to install trojai_rl module into Python environment
|   requirements.txt - A list of Python dependencies for pip
│   developers - information for developers
|   notebooks - A directory for Jupyter notebooks with example code
│   scripts - integration scripts showcasing API functionality
└───trojai - top level Python module
    └───datagen - submodule with implemented RL environments
    └───modelgen - model generation submodule
    └───test - top level scripts directory
        └───datagen - contains unittests for the datagen submodule
        └───modelgen - contains unittests for the modelgen submodule
```

## Acknowledgements
This research is based upon work supported in part by the Office of the Director of National Intelligence (ODNI), Intelligence Advanced Research Projects Activity (IARPA). The views and conclusions contained herein are those of the authors and should not be interpreted as necessarily representing the official policies, either expressed or implied, of ODNI, IARPA, or the U.S. Government. The U.S. Government is authorized to reproduce and distribute reprints for governmental purposes notwithstanding any copyright annotation therein.
