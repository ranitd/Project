Software that simulates the behaviour of systems written in the Beacon Calculus. bcs is under development by the Boemo Group at the University of Cambridge.

Downloading and Compiling bcs
Clone the bcs repository by running:

git clone https://github.com/MBoemo/bcs.git
The bcs directory will appear in your current directory. bcs was written in C++11 and uses OpenMP for parallel processing, but these are standard on most systems; there are no other third party dependencies. Compile the latest version of bcs by running:

cd bcs
git checkout v1.0.1
make
This will put the bcs executable into the bcs/bin directory. Development was done using gcc 5.4.0 on an Ubuntu 16.04 platform, and bcs was tested to compile and run on both OSX and Linux systems.

Documentation and Manual
A manual for writing models in the Beacon Calculus and documentation for bcs is available at https://beacon-calculus-simulator.readthedocs.io. It includes:

quick-start tutorials,
a bank of examples,
a full list of features.
