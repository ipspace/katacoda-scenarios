* Install netsim-tools: https://netsim-tools.readthedocs.io/en/latest/install.html

`git clone https://github.com/ipspace/netsim-tools/ && pip3 install -r netsim-tools/requirements.txt --ignore-installed`{{execute}}

* Install Containerlab: https://containerlab.srlinux.dev/install/

`sudo bash -c "$(curl -sL https://get-clab.srlinux.dev)"`{{execute}}

* Install Ansible

`sudo pip3 install ansible`{{execute}}

* Install Ansible **community.general** connection to get the latest version of Docker connection plugin.

`ansible-galaxy collection install community.general`{{execute}}
