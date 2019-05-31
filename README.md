# useqip-exercises
This repository contains exercises for the USEQIP 2019 Qiskit tutorial.

## Getting Started
First you will need to get started by [installing Qiskit](https://github.com/Qiskit/qiskit/blob/master/docs/install.rst).

This tutorials and exercises use jupyter notebook and matplotlib so install these as well

```bash
conda install jupyter matplotlib
```

The exercises use the `Exercise` extension for Jupyter notebook, install this with

```bash
conda install -c conda-forge jupyter_contrib_nbextensions
```
and enable
```bash
jupyter nbextension enable exercise/main && jupyter nbextension enable rubberband/main
```

Now run the Jupyter notebook server

```bash
jupyter notebook
```
and get started by opening the `exercises/0_getting_started.ipynb` notebook. Make sure to get the IBMQ account token and URL from your instructors.

## Questions?
Ask! Feel free to email us with any additional questions or ask in our community [Slack channel](https://join.slack.com/t/qiskit/shared_invite/enQtNjQ5OTc5ODM1ODYyLTBlMWY1ZGJiYmZkNjliZTY4MTViNTQ3NzI2ZmU2MzQxZjlhZDZlYTAzZTNlMDU0ZjVmNzEyMzY3OGE1Y2UyNjk).

## What to Contribute?
Qiskit is opensource and we love to work with our amazing community. We're aiming to build the defacto standard quantum computing framework and always welcome new contributors and researchers. Check out our [contributing guidelines](https://github.com/Qiskit/qiskit/blob/master/.github/CONTRIBUTING.md).
