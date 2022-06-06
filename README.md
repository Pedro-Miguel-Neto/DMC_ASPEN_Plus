# UBE_DMC_ASPENPlus
A chemical engineering project for the design of a DMC production plant. The process is based on several registered patents and is purely academic. The process was simulated in Aspen Plus.



Using Aspen+ I was able to calculate the process streams and equipment specs. The ASPEN Plus files should contain the converged results, if not, reset the results and run the simulation. 
Sometimes you might have to run the simulation more than once due to instabilities of the convergence methods.

The reactive distillation column file contains the Fortran subroutine (and all of the required files) that are used to perform the programmed kinetic calculations.
In case there is a warning stating the lack of some file, check in the settings menu if the correct path for the "usrknt3objdll_opt.opt" file is selected.
The rate-based distillation column was a little too much to ask for the convergence of the global process, however our studies demonstrate that the results can be approximated to an equillibrium formulation as it was done in the global process.

The project report (sadly in portuguese) explains how me and my colleagues detailed and designed all of the process equipments and plant formulation after the simulations.
