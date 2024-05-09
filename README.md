# EBSD_Data_example
Set of EBSD scans in .ctf format to test MTexTools functionality issues

The repository contains .ctf files exported from Bruker ESPRIT. They correspond to a large area map acquired in 10 acquisitions, arranged in a 2x5 grid (ixj). Where the correspondence of the files to the position in the grid is as follows:

R1_1 (1,1)
R1_2 (1,2)
R1_3 (1,3)
R1_4 (1,4)
R1_5 (1,5)
R1_6 (2,5)
R1_7 (2,4)
R1_8 (2,3)
R1_9 (2,2)
R1_10 (2,1)

The crystal symmetry is:

CS = {... 
  'notIndexed',...
  crystalSymmetry('4/mmm', [3.6 3.6 5.2], 'mineral', 'Zirconium oxide', 'color', [0.53 0.81 0.98]),...
  crystalSymmetry('m-3m', [4 4 4], 'mineral', 'Al2O3', 'color', [0.56 0.74 0.56])};
