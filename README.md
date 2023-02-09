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

## Setup

1. Install python from [python.org](https://www.python.org/downloads/).
2. Clone or download and unzip this repository.
3. (optional) I would suggest setting up a virtual environment inside the retrieved folder by running `python -m venv venv` and then activating this environment on windows with `venv\Scripts\activate`. Remember that if you want to use this code at some future point you might need to reactivate the virtual environment.
4. Install the needed packages with `pip install jupyter notebook onnxruntime matplotlib simfile`
5. Start up jupyter notebook with `python -m jupyter notebook`. Which will start a file browser tab on your standard browser.
6. Navigate to and open `Using Machine Learning to Understand and Improve StepMania Play.ipynb`.
7. Now follow the instructions in the jupyter notebook. You can run a cell with either shift+enter or the "play" button at the top.
