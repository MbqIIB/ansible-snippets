### Example commands

```shell
ansible all -m file -a 'path=/etc/fstab'
ansible all -m file -a 'path=/etc'
ansible all -s -m file -a 'path=/tmp/etc state=directory mode=0700 owner=root'
```
