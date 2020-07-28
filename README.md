## [NA2020](https://na2020.onrender.com/) Numerical Astrophysics Online Workshop

### Manuals

- [Anaconda](https://github.com/Shenavar/Anaconda-Installation.md/blob/master/Anaconda%20Installation.md)
- [Rebound](manuals/rebound.md)
- [Pluto](https://github.com/nghafourian/test/blob/master/Pluto.md)
- [fft (Fast Fourier transform)](https://github.com/Shenavar/Anaconda-Installation.md/blob/master/fftw3.md)

### codes

- [Pluto](http://plutocode.ph.unito.it/). Please note that we found a typo in the official code v. 4.3. that causes problem for it to work with python 3.x. We have prepared a [fix](codes/patch_define_problem) that solves this issue. You can download this fixed version from [here](https://github.com/astrofum/na2020/raw/master/codes/PLUTO.tar.gz).

### Materials sent by Prof. Kley
- All materials provided by Prof. Kley, including a basic introduction to numerical hydrodynamics, a project focused on linear advection, and some background on programming languages are available [here](https://www.tat.physik.uni-tuebingen.de/~kley/talks/mashad/index.html).

- The [Pyro Hydro Code](https://pyro2.readthedocs.io/en/latest/).

### Materials sent by Dr. Schäfer
- All the materials sent by [Dr. Christoph Schäfer](https://www.tat.physik.uni-tuebingen.de/~schaefer/) for the crash course, including slides and exercises, plus an introduction to N-Body Simulations with REBOUND, could be found [here](https://www.tat.physik.uni-tuebingen.de/~schaefer/teach/fum2020/).


### Materials sent by Dr. Bhargav Vaidya
- Here are the materials and explanations sent by [Dr. Bhargav Vaidya](http://www.iiti.ac.in/people/~bvaidya/index.html): 

In this [link](https://github.com/astrofum/na2020/blob/master/PLUTO_4.3_Mashhad2020.tar.gz), you will find the tar ball of the PLUTO v4.3 code to be installed for the students in the school.

Also pyPLUTO compatible for python >3.6 is present in Tools/pyPLUTO/pyPLUTO_v3.tar.gz 

Please install the pyPLUTO following the below steps:

- How to INSTALL:

Step 1 : Go to Tools/pyPLUTO folder in $PLUTO_DIR

Step 2:  Untar the pyPLUTO_v3.tar.gz file using the command : tar -xvzf pyPLUTO_v3.tar.gz

Step 3:  Now run the command - python setup.py install —user

Step 4: This shall create some additional files and folders. But most important it will create a file
```sh
$PYTHONPATH/pyPLUTO_v3-4.4.1-py3.7.egg
````

Check if this is created 

THIS INSTALLS the new version. 

- Getting Started:

Go to the folder where you have data files with *.out files and open the python 3 prompt. 

To read say data.0003.dbl file you need

import pyPLUTO_v3.pload as pp (PLEASE NOTE THE CHANGE)

D = pp.pload(3)

Then D.rho, D.prs, D.vx1 etc are variables. 



### BigBlueButton(BBB)

- Please check the [BBB manual](https://github.com/astrofum/na2020/blob/master/BigBlueButton.pdf) to get familiar with the platform.  
