### Example commands

```shell
ansible server2 -m setup -a 'filter=*cores*'
ansible server2 -m setup -a 'filter=ansible_processor_cores'
ansible server2 -m setup -a 'filter=ansible_architecture'
ansible server2 -m setup -a 'filter=ansible_dist*'
ansible server2 -m setup -a 'filter=ansible_distribution'
ansible server2 -m setup -a 'filter=ansible_domain'
ansible server2 -m setup -a 'filter=ansible_kernel'
ansible server2 -m setup -a 'filter=ansible_memtotal_mb'
ansible server2 -m setup -a 'filter=ansible_proc*'
ansible server2 -m setup -a 'filter=ansible_processor_count'
ansible server2 -m setup -a 'filter=ansible_virt*'
```
