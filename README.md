# paleo-bgc
Paleo-BGC model

The Paleo-BGC model is a close derivative of the original BIOME-BGC model from the Numerical Terradynamics Simulation Group (NTSG) at the Unviersity of Montana (http://www.ntsg.umt.edu/project/biome-bgc.php).  Details of the changes and additions of Paleo-BGC frmo BIOME-BGC are detailed in White et al. (in press) "A Process-Based Ecosystem Model (Paleo-BGC) to Simulate the Dynamic Response of Late Carboniferous Plants to Elevated O2 And Aridification"  American Journal of Science.

The code provided here is solely for research and education purposes.  It is distributed "as is" with implementation and simulation responsiblity of the end user.

Notes:
- All source code, libraries, and demonstration makefile are found in the /src folder. 
- For this original project, the code was compiled on a PC with Windows 10 using gnu Windows 32 with gcc.
- End users will need to modify the provided makefile for their computing environment.
- To change atmospheric oxygen in this version, the end use must change appropriate variable is the bgc_constants.h file before compilation.  Two representative files titiled bgc_constants_pO2_21.h and bgc_constants_pO2_28.h are provided as examples of atmospheres with 21 and 28% oxygen, respectively.
- Initialization filed used inthis project are provided in the /ini file.  When executing the code, each of these ini files must be specific explicitly.
- The ecophysiological files for each of the modern and paleo palnt types are provided in the /epc directory.
- The meteorological data extracted from the GENESIS simulations for pCO2=600 ppm and 21% O2 for the tropical wet Pangaea location are provided in the /met directory.  This contains 10 years of daily data.
- The /co2 director is provided solely as legacy.  It contains a recent CO2 record and was not used in this project.
