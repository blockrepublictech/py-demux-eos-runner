# Python Demux Runner

A small utility that test the py-demux-eos module is correct and can be installed
and run normally

## Instructions

```
virtualenv venv -p python3

source venv/bin/activate

pip install --upgrade pip

pip install --upgrade setuptools urllib3[secure]

pip install git+https://github.com/mlockett42/py-eos-api@46c25eae0ecce048cd85b97d06534c8bbd390a35

pip install  git+https://github.com/mlockett42/py-demux@bbe6cafe82eb176b1ab098f4ffd5b3b933be8e08
```

You can you run the runner.py function to use some rudimentary functions

```
python runner.py
```
