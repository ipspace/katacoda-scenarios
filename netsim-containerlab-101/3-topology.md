**netsim-tools** uses simple network topology files in YAML format. The network topology should contain nodes (devices), links between them, protocols running in the network, and protocol parameters.

Our lab topology is defined in `frr-topology.yml` file. Let's look at it:

`cat frr-topology.yml`{{execute}}

Here's what that file is saying:

* The lab has three **nodes** (r1, r2 and r3) and two links (r1-r2 and r2-r3). 
* We'll use **frr** devices on **containerlab** (*clab*)
* We want to run OSPF and BGP on all devices.
* We want to have two BGP autonomous systems. R1 and R2 will be in AS 65000, R3 will be in AS 65001.
