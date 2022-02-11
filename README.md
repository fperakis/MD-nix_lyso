# MD-nix_lyso
An example of runing MD simulations using gromacs at Fysikum HPC. 
https://it.fysik.su.se/hpc/

Here is simulated several lysozyme molecules in water/glycerol mixture.

The packages are initialised using NixOS, see here. 
https://github.com/markuskowa/NixOS-QChem

-----

## USAGE

### connecting to the cluster

Using ssh
```bash 
ssh -p 31422 username@sol-nix.fysik.su.se
```
and sshfs
```bash
sshfs -p 31422 username@sol-login.fysik.su.se:/cfs/home/username /local_folder
```
