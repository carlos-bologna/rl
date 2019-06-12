# That is my gym of reinforcement learning, welcome.

Some tips to run it in Linux (of course).

## Clone it
```
$ git clone https://github.com/carlos-bologna/hospital-length-of-stay.git
```
## Create a Python enviroment with Conda
```
$ conda create -n rl python=3.6
```
then...
```
$ conda activate rl
```
## Install Packages
```
$ conda install --file requirements.txt
```
## Add Jupyter Notebook Kernel
```
$ python -m ipykernel install --user --name=rl
```
then
```
$ jupyter notebook
```
