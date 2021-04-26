* Use familiar show commands like **show ip bgp summary** or **show ip bgp** to inspect the OSPF neighbors, BGP neighbors, BGP table, or IP routing table

`show ip bgp summary`{{execute}}

`show ip bgp`{{execute}}

`show ip route`{{execute}}

* Disconnect from vtysh and current container with **exit** or ctrl-D.

`exit`{{execute}}

* Keep pressing exit until you get the shell prompt ($)
* Connect to another device (R1) with **connect.sh**

`connect.sh r1`{{execute}}

* Ping a router in another autonomous system (the /etc/hosts file has been created during the initial configuration). Use -I option to specify the source IP address (the loopback interface).

`ping -I 10.0.0.1 r3`{{execute}}

* Inspect the Ansible inventory file (**hosts.yml**), Ansible host variables (in **host_vars** directory) or Ansible group variables (in **group_vars** directory).
