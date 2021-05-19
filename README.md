# ansible-inventory-ci-duffy
Ansible inventory used by Duffy provisionner system for infra behind ci.centos.org

This inventory *isn't* the real infra but just a temporary inventory that is only used by Duffy to deploy bare-metal nodes (pets vs cattles)
So basically just contains mac addresses needed for the hosts to be fully reinstalled on demand by duffy worker, calling ansible and using this inventory transparently
Some inventory files with some level of creds are crypted with `ansible-vault`
