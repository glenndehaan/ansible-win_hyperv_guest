# Ansible Windows Hyper-V Guest Module

An Ansible module to control Hyper-V VM's from Ansible

## Structure
- Python
- YAML
- Powershell

## Basic Usage
- Install Ansible 2.4
- Run `pip install pywinrm`
- Run `ansible-playbook -i ./src/hosts ./src/create_vm.yml`

## Notes
- This module has been tested on Ubuntu 16.04 running Ansible 2.4 (Hyper-V Server: Windows Server 2012 R2)
- Run the following script on the Windows machine in order for Ansible to be able to connect to the machine: https://github.com/ansible/ansible/blob/devel/examples/scripts/ConfigureRemotingForAnsible.ps1

## License

MIT
