# UWO Wind Tunnel Output

This directory contains the `line` output files from FDS for the University of Western Ontario (UWO) Wind Tunnel experiments. The FDS `line` file contains linear arrays of pressure coefficients on the various faces of the model building in the wind tunnel. There is a script in the `fds` repository called `Utilities/Matlab/scripts/UWO_Wind_Tunnel.m` that reads the line files and creates a new file for each continuous array of linear profiles. The file called `UWO_inputs.csv` in this directory lists the column numbers in the `line` files where the spatial coordinates are located, mean, rms, min and max values. 