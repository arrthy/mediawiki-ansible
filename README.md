# mediawiki-ansible

This ansible playbook is for the installation of Mediawiki with loadbalancing, written to run on Redhat platform

Execute the playbook using below command:

ansible-playbook -vv --ask-vault-pass -i inventory/hosts playbook.yml