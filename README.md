# OpenPOWER Foundation - OpenPOWER General Information #

The OpenPOWER Foundation is a collaboration around Power ISA-based community.  
The goal is to enable the ecosystem to build computing solutions with their own customization.  

The Foundation is a non-profit serving its member entities and the open developer community for the POWER architecture.  
The OpenPOWER Foundation also releases Documentation, Specifications, References on the POWER Architecture.  

The main git repositories are hosted on https://git.openpower.foundation running Open Source Technology on POWER based hardware.  
We maintain public repository mirrors with GitHub, and GitLab for user convenience, however some repositories may only exists on OPF Git.  

For members, please use your OPF Passport to log into https://git.openpower.foundation/.  
For non-members, you can interact through GitHub, GitLab, or OPF Git, using your existing credentials.  


## Non-Mirrored Repository List ##

- OpenPOWER Public Website (_https://openpowerfoundation.org_ or _https://openpower.foundation_)  
  https://git.openpower.foundation/website/openpower.foundation/


## Mirrored Repository List ##

### LibreBMC SIG ###

- __LPC Peripheral__ : This is an LPC peripheral that implements LPC IO and FW cycles so that it can boot a host like a POWER9. This peripheral would typically sit inside a BMC SoC.
  https://git.openpower.foundation/librebmc/lpcperipheral
  https://github.com/OpenPOWERFoundation/lpcperipheral
  https://gitlab.com/openpowerfoundation/lpcperipheral

- __AC922 Interposer DC-SCM v1.0__ : 
  https://git.openpower.foundation/librebmc/ac922interposer
  https://github.com/OpenPOWERFoundation/ac922interposer
  https://gitlab.com/openpowerfoundation/ac922interposer
  https://gitlab.com/librebmc/ac922interposer

### Core BoF ###

- __A2O Core__ : The A2O core was a follow-on to A2I, written in Verilog, and supported a lower thread count than A2I, but higher performance per thread, using out-of-order execution (register renaming, reservation stations, completion buffer) and a store queue
  https://git.openpower.foundation/cores/a2o

- __A2I Core__ : The A2I core was used as the general purpose processor for BlueGene/Q, the successor to BlueGene/L and BlueGene/P supercomputers
  https://git.openpower.foundation/cores/a2i

- A2P Core : 
