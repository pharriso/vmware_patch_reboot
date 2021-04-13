Patch linux vms on VMware
=========

Inventory
--------------

Configure the inventory file with a list of hosts you want to patch.

Credentials
--------------

Either remove the VMware credential parameters if running in Tower or add the relevant variables. Use ansible-vault or some other vault to encrypt credentials.

Running the playbook
--------------

```bash
ansible-playbook snap_patch_reboot.yml -i inventory
```
