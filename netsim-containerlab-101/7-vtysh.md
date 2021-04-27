FRRouting uses its own CLI which is so similar to Cisco IOS CLI that you can usually get the job done without looking up the documentation.

Use **vtysh** command in **bash** to connect to the FRR daemon running on the same host.

`vtysh`{{execute}}

Now you can use the familiar **show** commands to display device or protocol information. Let's look at the interface descriptions first:

`show interface description`{{execute}}
