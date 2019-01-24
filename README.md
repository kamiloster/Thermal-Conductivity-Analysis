# ThermalConductivityAnalysis
This script was prepared for the analysis of data obtained from the measurement of thermal conductivity.

The input data are loaded via fileopenbox(). However, the input must be pre-processed: 
  a) saved as csv file with x and y columns
  b) x column is time in seconds
  c) y column is temperature in Kelvin
  
Finally, a .jpg file is created with the output: temperature, slope, density, heat capacity, thermal conductivity in a plot with T(t).

For wider use, the standalone executable file was created with pyinstaller.
