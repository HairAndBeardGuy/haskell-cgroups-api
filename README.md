haskell-cgroups-api
===================

This software is an experiment.

A job has been advertised requiring the following:


Write a FastCGI or HTTP program in Haskell that provides a restful API to manage the cgroups of a server. It should support the following:

* create a cgroup
* place a process into a cgroup
* list the tasks (PIDs) for a given cgroup

 _You can assume that the server is running a Linux 3.4 kernel with the cgroup root mounted via sysfs._  
 Include a default.nix to build your program as a nix package. Bonus points for including a NixOS module.nix.
 
This task will require an understanding of the following:

* Haskell
  * FastCGI / HTTP with Haskell
* cgroups
* managing processes
* accessing PIDs and filtering by cgroup
* cgroup root mounting via sysfs
* NixOS
  * nix packages
  * default.nix to build program as nix package
  * NixOS module.nix
