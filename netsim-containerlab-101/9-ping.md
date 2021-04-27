Connect to *R1* with **connect.sh**

`connect.sh r1`{{execute}}

Let's try to ping a router in another autonomous system from the loopback IP address. We'll use the Linux **ping** command, so we have to use the **-I** option to specify the source IP address.

**initial-configuration.ansible** script created /etc/hosts file for us, so we can use the remote device name (*r3*) instead of trying to figure out what its IP address is.

`ping -I 10.0.0.1 r3`{{execute}}

The guided tour is now over. You know:

* How to connect to FRR containers
* How to execute Linux commands
* How to connect to FRR CLI (**vtysh**)
* How to execute FRR **show** commands
* How to get back to the original **bash**

Please feel free to explore the network, and modify device configurations -- just pretend you're working with Cisco IOS and you'll probably be just fine.