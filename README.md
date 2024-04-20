VAULT and Consul HA PROVISION
=============================

Role Variables
--------------

* Consul vars:
  - `consul_binary_dir`
  - `consul_config_dir:`
  - `consul_data_dir`
  - `consul_datacenter`

* Vault vars:
  - `vault_binary_dir`
  - `vault_config_dir`

See [vault-consul-ha-provision/defaults/main.yml](./vault-consul-ha-provision/defaults/main.yml)

Dependencies
------------

* Remote access 
* Inventory
  - Refering to the group as `consul_machines` and `vault_machines`

Example Playbook
----------------

See 
* [playbook.yaml](./playbook.yaml) 

Execution example:

* `ansible-playbook -i inventory playbook.yaml` 

