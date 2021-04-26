* Install netsim-tools: https://netsim-tools.readthedocs.io/en/latest/install.html

`git clone https://github.com/ipspace/netsim-tools/ && pip3 install -r netsim-tools/requirements.txt --ignore-installed`{{execute}}

* Install Containerlab: https://containerlab.srlinux.dev/install/

`sudo bash -c "$(curl -sL https://get-clab.srlinux.dev)"`{{execute}}

* Install Ansible

`sudo pip3 install ansible`

* (Optional) get 4GB extra swap space

`mkdir /root/dev; fallocate -l 4G /root/dev/md-0; chmod 600 /root/dev/md-0; mkswap /root/dev/md-0; swapon /root/dev/md-0`{{execute}}

* Make life easier by enabling auto-completion of shell commands:

`source <(containerlab completion bash)`{{execute}}
