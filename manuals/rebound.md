### [Rebound](https://rebound.readthedocs.io/en/latest/) installation

Install git:

`sudo apt-get install git`

Install C and fortran compilers as well as build utilities:

`sudo apt-get install gcc gfortran build-essential`

Install portable library for OpenGL, window and input (development files):

`sudo apt-get install libglfw3-dev`

Then clone rebound source code repository:

`git clone http://github.com/hannorein/rebound`

Go to an example:

`cd rebound/examples/shearing_sheet`

Now compile and make the code:

`make`

And Finally run the code:

`./rebound`
