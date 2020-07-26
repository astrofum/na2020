# [Rebound](https://rebound.readthedocs.io/en/latest/)
## A simple guide for installation on GNU/Linux OS (ubuntu based distros)


Install git:

`sudo apt-get install git`

Install C and fortran compilers as well as build utilities:

`sudo apt-get install gcc gfortran build-essential`

Install portable library for OpenGL, window and input (development files):

`sudo apt-get install libglfw3-dev`

Then clone rebound source code repository:

`git clone http://github.com/hannorein/rebound`

Go to an example:

`cd rebound/examples/selfgravity_plummer`

Now compile and make the code:

`make`

And Finally run the code:

`./rebound`

Please also see [here](https://github.com/hannorein/rebound/blob/master/doc/c_quickstart.rst) for a more detailed user guide.


## How to install rebound on Windows 10 by Christoph Schaefer

We are thankful to [Prof. Christoph Schaefer](https://www.tat.physik.uni-tuebingen.de/~schaefer/) for providing this manual on how to install rebound on Windows 10. You may simply click [here](https://github.com/astrofum/na2020/blob/master/how_to_install_rebound_on_win10%20by%20Christoph%20Schaefer.pdf) to download the manual.
