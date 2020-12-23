# MSS (Marine Systems Simulator)

The Marine Systems Simulator (MSS) is a Matlab/Simulink library for marine systems. It includes models for ships, underwater vehicles, and floating structures. The library also contains guidance, navigation, and control (GNC) blocks for real-time simulation. The algorithms are described in:

**T. I. Fossen (2021).** *Handbook of Marine Craft Hydrodynamics and Motion Control*. 2nd. Edition, Wiley. ISBN-13: 978-1119575054

which serves as documentation for the toolbox. Please include the following reference when you use the MSS libraries: 

**T. I. Fossen and T. Perez (2004).** *Marine Systems Simulator (MSS)*.
URL: https://github.com/cybergalactic/MSS

Copy the folder /MSS to your Matlab folder and "add the path with subfolders" to Matlab. Then type:

    help MSS

 GNC Library
-

Basic libraries and system examples for guidance, navigation and control (GNC). The library contains:

- M-file functions (kinematics and kinetics) and examples for time-domain GNC applications.
- M-file library with vessels models, maneuvering trials and dynamic simulation.
- User editable m-files for simulation and control of marine craft including ships, semi-submersibles, autonomous underwater vehicles (AUVs), remotely operated vehicles (ROVs) and unmanned surface vehciles (USVs).
- User editable m-files for model-based and inertial navigation systems.

 HYDRO Library
-

The toolbox reads output data files generated by hydrodynamic programs and processes the data for use in Matlab. MSS Hydro includes several example vessels. In order to build your own model, you need a license for one of the following programs:

- 2D strip theory programs - ShipX (Veres) by SINTEF OCEAN AS
- 3D potential theory programs - WAMIT by WAMIT Inc.

The processed data can be used in real-time simulation of marine vessels in 6 DOFs exposed to 1st- and 2nd-order wave loads (motion and force RAO transfer functions).

FDI Toolbox
-
This is a stand-alone toolbox for identification of radiation-force models and fluid memory effects of marine structures such as marine craft and wave energy converters. Please include the following reference when you use the MSS FDI toolbox:
 
**T. Perez and T. I. Fossen (2009).** A Matlab Tool for Parametric Identification of Radiation-Force Models of Ships and Offshore Structures. 
*Modelling, Identification and Control*, MIC-30(1):1-15. DOI: https://doi.org/10.4173/mic.2009.1.1 
