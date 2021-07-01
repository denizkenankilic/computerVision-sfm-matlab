# computerVision-sfm-matlab
Structure From Motion

In this repository you will find Matlab codes and sample files to test codes for the SFM (structure from motion) algoritm.

Main code is the "GetFmatrix_final.m" file by J.H.KIM. The "intrinsic_matrix.txt" file contains the camera intrinsic values. Besides, the other .txt files are the selected middle corner points of the chess boards. Basically, after calculating the fundamental matrix (F) the essential matrix (E) and the camera pose are estimated. Then the 3D data is reached by using the triangulation method. Clear explanations of the steps for the SFM are given in:

https://cmsc426.github.io/sfm/
