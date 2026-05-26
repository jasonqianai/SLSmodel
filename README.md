# SLSmodel

1.	System requirements: 

  •	Require software: MATLAB
  
  •	Version that has been tested on: MATLAB R2021b on Windows 10 Enterprise 22H2
  
  •	The code is executable on any operating systems with any version of MATLAB installed.


2.	Installation guide:

  •	No installation is required. The code is executable on MATLAB only. You need to install MATLAB first at Download and Install MATLAB - MATLAB & Simulink


3.	Demo:

  •	Instructions to run the data: Once the file is opened in MATLAB, click “Run”, it will run automatically.
  
  •	Expected output: When you open the .mlx file in MATLAB, expected output will show up on the side of MATLAB window. You can also find the a Expected_output.pdf file to view the expected output.
  
  •	Expected run time for the demo code on a “normal” desktop computer: 30 seconds.


4.	Instructions for use

  •	How to run the software on your data: 

    i.	Replace the ETCF function at the end of the code with your system’s ETCF.
    
    ii.	Replace the substrate coordinates variable “atomcoor” with the xyz coordinates of your substrate atoms in space. 
    
    iii.	Click “Run”.

  •	Reproduction instructions: To reproduce the density maps in the manuscript, we need to

    i.	Choose the corresponding ETCF from Supplementary Table 1 and 3 for the system you want to reproduce.
    
    ii.	Use the substrate structure illustrated in the density map you want to reproduce. E.g., for a bi-step HOPG, we can add another layer of graphene on top of existing mono-step HOPG coordinates. 
