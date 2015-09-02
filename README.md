# ansible-ipython-notebook-server

Provision an IPython notebook server on a Linux CentOS 7 VM.

## Start the virtual machine

```
vagrant up
```

## Provision the virtual machine

```
cd provisioning
ansible-playbook -i hosts base.yml
```
