# This folder contains the trained artificial neural networks and a code to load them.
#
# To execute the trained neural network it is necessary to compile:
# xx_ANN.f90, fann.F90, NN_XX.dat and dV_XX.dat.
# where XX = O2, N2 or S0
#
# For example. System O2:
# gfortran fann.F90 o2_ANN.f90 -o out.x -lfann -lm

# However, to run these codes it is necessary to have installed in your computer the Fast Artificial Neural Network (FANN) Library. For such, the download can be realized in the page below. There, all instructions to install this library is given in details.   

# http://leenissen.dk/fann/wp/
