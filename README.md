# ansible-learn

https://www.udemy.com/course/docker-ansible/learn/lecture/27553026#reviews

```
ansible -i aynur-inventar/hosts.ini -m user -a "name=root state=absent"  demo
```

### running ansible-playbook

    ansible-playbook -i aynur-inventar/hosts.ini aynur-inventar/user.yml

### password

ansible-playbook -i aynur-inventar/hosts.ini aynur-inventar/user.yml -K

### vault

    ansible-vault encrypt group_vars/all/vault.yml

    ansible-vault decrypt group_vars/all/vault.yml

    ansible-vault view group_vars/all/vault.yml
