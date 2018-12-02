# Python Demux Runner

A small utility that test the py-demux-eos module is correct and can be installed
and run normally.

The main py-demux-eos source cod is available at [https://github.com/blockrepublictech/py-demux-eos]

## Instructions

```
virtualenv venv -p python3

source venv/bin/activate

pip install --upgrade pip

pip install --upgrade setuptools urllib3[secure]

pip install git+https://github.com/blockrepublictech/py-demux-eos.git@54586e1696b52c81f8c4a3969c2844d7a65c5dee
```

You can you run the runner.py function to use some rudimentary functions

```
python runner.py
```
