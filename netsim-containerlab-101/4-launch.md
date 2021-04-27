**netsim-tools** uses its topology file to create a Vagrant or containerlab configuration file (**clab.yml**), Ansible inventory, and Ansible configuration file (**ansible.cfg**).

* Create the configuration files:

`create-topology -t frr-topology.yml -p -i -c`{{execute}}

* Launch the lab:

`sudo containerlab deploy -t clab.yml`{{execute}}

You might want to inspect the files created by **create-topology** script before moving on. To do so, click on the terminal window, and use the standard Linux commands.
