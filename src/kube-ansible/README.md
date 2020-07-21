# Running the Ansible Playbook
1. Create an inventory file named `inventory` with groups `master_hosts`, `etcd_hosts`, `worker_hosts` and `ingress_hosts`. See example below.
2. ansible-playbook -i inventory playbook.yaml

## Inventory file example
```Ini
[master_hosts]
10.45.138.227
10.45.138.113
10.45.138.226

[etcd_hosts]
10.45.138.63
10.45.138.121
10.45.138.125

[worker_hosts]
10.45.138.143
10.45.138.108
10.45.138.243

[ingress_hosts]
10.45.138.151
```
