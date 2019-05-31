Overview
--------

This package contains the simulation software for 

Tripp & Eliasmith (2010) Population models of temporal
differentiation, Neural Computation. 22(3):621-59

This software is not self-contained -- it runs within the Nengo
simulation environment (www.nengo.ca). The enclosed code consists of
Java classes, which contain the models, and Python scripts, which
automate loading and simulation of the models.

Browsing The Code
-----------------

If you just want to see precisely how we did something, you may want
to read the Java code. This code is based on the Nengo API, which is
documented at http://nengo.ca/javadoc/index.html A good place to start
is the class com.bptripp.diff.DifferentiatorNetwork, which is the
parent class for all of the models.

Running the Code
----------------

1) Download and install Nengo from www.nengo.ca
2) Add the enclosed diff.jar (which contains compiled versions of the
Java classes) to the "plugins" directory under the Nengo install.
3) Start Nengo. 
4) Open the Python script console within Nengo, and type "run
[path]loadNetworks.py" where [path] is the path to your copy of the
Python scripts.

You may then run other scripts of interest, e.g. simulations.py.

Help 
----

If you run into difficulties, please do not hesitate to contact Bryan
Tripp (bptripp at gmail.com).
