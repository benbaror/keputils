__Basic module for interaction with KOI and Kepler-stellar tables.__

Requirements: `pandas` module.

To set up data files, run './getdata.sh' from command line.  This will create a ~/.keputils folder, into which the current cumulative KOI and keplerstellar tables will be saved as .csv files.

The first time you import, the .csv files will be read in and the data saved to an .h5 file in ~/.keputils.  After that, loading the module will be faster.
