# Kafka ansible playbook for Ubuntu 20.04

Kafka ansible install for homelab

copy example inventory folder

```
cp -R inventory/server inventory/homelab
```

Adjust `hosts.ini` and some variables on `group_vars`.
change `ansible_user` as your remote machine user

run

```
ansible-playbook kafka.yaml -i inventory/homelab/hosts.ini -K
```

and split your coffee.
