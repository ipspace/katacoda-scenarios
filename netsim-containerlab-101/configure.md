* Initial configuration of FRR containers creates loopback interfaces, and sets the interface addresses and hostnames.

`initial-config.ansible -t initial`{{execute}}

* Configure OSPF and BGP (the modules specified in netsim-tools topology file). Use **-v** flag to print the configurations before they're deployed.

`initial-config.ansible -t module -v`{{execute}}

* Connect to a FRR container:

`connect.sh r2`{{execute}}

* Use **vtysh** to connect to the FRR daemon (which emulates the *industry-standard* CLI)

`vtysh`{{execute}}
