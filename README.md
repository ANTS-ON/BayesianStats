[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ANTS-ON/BayesianStats/HEAD)

Bayesian Statistics from Scratch
---

Short introduction to Bayesian statistics with a script and some exercises.

### Installation
In order to execute the script and do the exercises, you need a virtual environment with several packages (`jupyter`, `pymc`, ...). You can simply create the environment by creating a virtual environment and installing packages from the `requirements.txt`.
```shell
python -m venv <env_name>
source <env_name>/bin/activate
pip install -r requirements.txt
```
Within this environment, just start a jupyter notebook server by
```shell
jupyter notebook
```
This should open an interactive view in your standard browser. From your browser, you can work on exercises and look at the interactive script.

### Binder
If you have trouble following the installation steps or your local python is not compliant, use a `binder` instance of the repository. Click on the badge above the title. This should redirect you to a `JupyterLab` instance in your browser with the repository and all necessary packages installed.

### References
The referenced material used to edit this workshop is also recommended for further readings.

*Literature*
- Bayesian Statistics and Modelling (van de Schoot et al., 2021), a very concise and well-readable primer (use first for further reading)
- Bayesian Data Analysis (Gelman et al., 2003), a very comprehensive book (use for referencing)
- Introduction to Probability and Statistics, MIT OpenCourseWare public lecture (use for covering the basics)
