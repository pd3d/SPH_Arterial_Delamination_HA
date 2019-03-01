# SPH_Arterial_Delamination_HA
This is the "Smoothed Particle Hydrodynamics" simulation code for the following published paper:
"Particle-based computational modelling of arterial disease", (2018). H. Ahmadzadeh, M. Rausch, J. Humphrey, Royal Society Interface.

The code is highly parallelized with mpirun and the input text files containing the coordinates of the particles and the input geometrical parameters are also included.

Please email me with your questions at: hsn.ahmadzadeh@gmail.com

Thank you!

### Windows

1. Install the latest version of [Python 3](https://www.python.org/downloads/windows/) by following the link, make sure to click on the ___"Add Python 3.x to PATH".___ This is very vital for the modules to be loaded.
<p align="center"><img src="https://simpleisbetterthancomplex.com/media/series/beginners-guide/1.11/part-1/windows/install-python.png" alt="python_addPath" width="550"/></p>

2. After Python has been installed, install the required modules by typing the following in a command prompt (make sure you are running command prompt as administrator)
```
py -3 -m pip3 install --upgrade pip
py -3 -m pip3 install numpy
py -3 -m pip3 install matplotlib
py -3 -m pip3 install mpi4py
py -3 -m pip3 install sklearn

```
