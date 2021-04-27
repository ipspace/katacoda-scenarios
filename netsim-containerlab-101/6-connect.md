The **connect.sh** script included in **netsim-tools** uses Ansible inventory created with **create-topology** to connect to the management IP address of a lab device or to a Docker container.

Use **connect.sh** script to connect to FRR container *R2*:

`connect.sh r2`{{execute}}

FRR runs on Linux, and when you connect to the container you get the usual **bash** prompt. You can use the Linux **ip** commands at this point to inspect interfaces and IP addresses.

`ip link`{{execute}}

`ip addr`{{execute}}

Use **vtysh** to connect to the FRR daemon (which emulates the *industry-standard* CLI)

`vtysh`{{execute}}
