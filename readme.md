# Python Demux Runner

A small utility that test the py-demux-eos module is correct and can be installed
and run normally

## Instructions

```
virtualenv venv -p python3

source venv/bin/activate

pip install --upgrade pip

pip install --upgrade setuptools urllib3[secure]

pip install  git+https://github.com/mlockett42/py-demux@e91ede7bdef915306f8dd02d53e15c5183a0331c
```

You can you run the runner.py function to use some rudimentary functions

```
python runner.py
```
