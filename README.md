# Meatball
This is the repository of a StepMania ML tool called Meatball which is based off of a model trained in the paper [Ordinal Regression for Difficulty Estimation of StepMania Levels](https://arxiv.org/pdf/2301.09485.pdf).

## Requirements
The jupyter notebook file herein was created with python 3.10.9, but will likely work with most versions. onnxruntime is likely the candidate deciding which python version can be used, since it does not support every python version.

* jupyter
* notebook
* onnxruntime
* simfile
* matplotlib

Just run `pip install jupyter notebook onnxruntime matplotlib simfile`

## Example Use

Start up the jupyter notebook with `python -m jupyter notebook` on the partition where you cloned this repository and follow the instructions in the jupyter notebook.
