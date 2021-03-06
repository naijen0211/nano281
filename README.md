# NANO281 - Data Science for Materials Science

Welcome to the official Github repo for UCSD Course NANO281 - 
"Data Science in Materials Science". Here, you will find the materials for all
lab sessions, as well as useful resources.

# Programming language

All lab sessions will be conducted in Python 3.7+/3.8+. Prior to the labs,
please do the following:

1. Install [python](https://www.python.org/) on your laptop.
2. If you are unfamiliar with Python, please minimally go through the official
   [Python tutorials](https://docs.python.org/3/tutorial/index.html) to
   understand the basics of variable assignment, if and for loops, etc. While
   we are not expecting advanced python knowledge, everything will go much
   quicker if you are already familiar with the basics.

# Preparing for your lectures and labs

In preparation for your lectures and labs, please ensure that you have your Python environment setup properly. You only need to do this once. There are alternative approaches to setting up your machine, but the approach outlined here is guaranteed to work and is reproducble.

1. Download the Python 3.7+ version of [Miniconda](https://docs.conda.io/en/latest/miniconda.html) (recommended) or [Anaconda](https://www.anaconda.com/distribution/) for your OS.
2. Follow the official instructions and install Miniconda/Anaconda.
3. Start the terminal (Mac/Linux) or Anaconda Prompt (Windows).
4. Create a virtual environment for NANO281:
```bash
conda create --name nano281 python=3.7
```
5. Activate the virtual environment.
```bash
conda activate nano281
```
6. Install the necessary Python libraries.
```bash
conda install --yes numpy scipy matplotlib pandas jupyter seaborn scikit-learn tensorflow
conda install --channel conda-forge --yes pymatgen
```
7. An alternative to steps 4-6 is to download the [nano281_env.yml](https://raw.githubusercontent.com/materialsvirtuallab/nano281/master/nano281_env.yml) file from the Google classroom or Github repo and create the environment directly.
```bash
conda env create -f nano281_env.yml
```
8. Subsequently, always activate your nano281 environment prior to working on your lectures/labs using:
```bash
conda activate nano281
```

# Course textbooks

The course is intended to be self-contained and all textbooks are optional.
However, the following are useful to have around:

1. The Elements of Statistical Learning: Data Mining, Inference, and Prediction,
   Second Edition [Amazon](https://www.amazon.com/dp/0387848576/ref=cm_sw_em_r_mt_dp_U_Z8r8DbR3HMYRE), or get the [free online version](https://web.stanford.edu/~hastie/Papers/ESLII.pdf).
2. Python Data Science Handbook. Buy from [Amazon](https://www.amazon.com/gp/product/1491912057/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1) or get the
   [free online version](https://jakevdp.github.io/PythonDataScienceHandbook/).


