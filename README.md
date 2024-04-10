# README

## lima instructions

```bash
limactl create --containerd none --vm-type vz --rosetta --name fedora --mount-writable template://fedora
```

## ansible instructions

Copy `inventory.tmpl` to `inventory` and adapt it to your situation (mainly change
'YOURUSERNAME' to your username), and run:

```bash
ansible-playbook setup.yml
```
