#########################################
####       Abhiram B R		           ####	
#### Department of Civil Engineering ####
####  Indian Institute of Science    #### 
####     abhirambr@iisc.ac.in 	     ####	
#########################################

------------------------------------------------------------------------------------------------------------------------------------------------------------------

This folder contains molecular dynamics (MD) codes to simulate the influence of agglomeration of functionalized carbon nanotube (CNT) on the 
fracture properties of polymer nanocomposite (PNC).
Modeling is performed in Materials Studio 6.0
The model is then imported to LAMMPS using msi2lmp tool
All MD simulations are performed in LAMMPS and the post-processing is performed using OVITO and MATLAB

------------------------------------------------------------------------------------------------------------------------------------------------------------------

The directory includes the following folders and files

Folder names:
single_cnt	- consists of MD code and dependent files for simulating fracture properties of PNC with single CNT reinforcement
equilibration   - MD code for running sequence of equilibration
tension		- MD code for running uniaxial tension boundary condition

File names:

in.equi_pmma_pnc	- MD code to simulate equilibration
in.pnc_tension_crack	- MD code to simulate uniaxial tension boundary condition on PNC with an initial crack

------------------------------------------------------------------------------------------------------------------------------------------------------------------

For any queries write to abhirambr@iisc.ac.in

References

1. Abhiram B R and Debraj Ghosh, Atomic investigation on optimal interfacial bonding for enhanced fracture properties in polymer nanocomposites, Engineering Fracture Mechanics (2023): 109078
