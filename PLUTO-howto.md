In this [link](https://github.com/astrofum/na2020/blob/master/PLUTO_4.3_Mashhad2020.tar.gz), you will find the tar ball of the PLUTO v4.3 code to be installed for the students in the school ( if they haven't installed PLUTO already ).

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
