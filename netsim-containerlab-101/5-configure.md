The **initial-config.ansible** playbook included in **netsim-tools** creates and deploys initial device configurations and configures all protocols specified in the configuration file. You can use Ansible tags to deploy *initial* or *module* (protocol) configuration.

* Configure interfaces, IP addresses, and hostnames of FRR containers:

`initial-config.ansible -t initial`{{execute}}

* Configure OSPF and BGP (the protocols specified in netsim-tools topology file). Use **-v** flag to print the configurations before they're deployed.

`initial-config.ansible -t module -v`{{execute}}

You might want to browse through the printouts and look at the configurations that were deployed on the devices -- they are very similar to what you would configure on Cisco IOS and Arista EOS.
