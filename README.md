# Ansible Skeletons

This is the skeletons I use when creating new playbooks. 

For new Ansible project just copy everything to the new project:

```sh
cp -R ansible-playbook/* /path/to/new_project/
```

For new Roles in a project just use ansible-galaxy

```sh
ansible-galaxy init --role-skeleton=./ansible-role/ /path/to/new_project/roles/new_role
```

Remember to have Ansible installed

```sh
python3 -m venv ~/ansible-env
source ~/ansible-env/bin/activate
pip3 install ansible
source ~/ansible-env/bin/activate
```
