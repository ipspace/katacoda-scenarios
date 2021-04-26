* Inspect the FRR topology file:

`cat netsim-tools/examples/frr.yml`{{execute}}

* Prepare the containerlab topology file, Ansible inventory, and **ansible.cfg**:

`create-topology -t netsim-tools/examples/frr.yml -p -i -c`{{execute}}

* Launch the lab:

`sudo containerlab deploy -t clab.yml`{{execute}}
