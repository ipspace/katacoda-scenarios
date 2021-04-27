Look around a bit. Use familiar show commands like **show ip bgp summary** or **show ip bgp**. Let's inspect BGP status, BGP table, and IP routing table:

`show ip bgp summary`{{execute}}

`show ip bgp`{{execute}}

`show ip route`{{execute}}

It's time to disconnect from *R2* and connect to another device. 
Disconnect from vtysh with **exit**.

`exit`{{execute}}

You're still connected to the FRR container. Use another **exit** command (or ctrl-D) to get back to the shell prompt.

`exit`{{execute}}
