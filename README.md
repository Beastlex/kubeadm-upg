# Ansible playbook for update cluster with kubeadm

## Insatll ansible
```console
python3 -m pip install --user ansible
```

## Install requirements
```console
ansible-galaxy install -r requirements.yml
```

## Fill inventory file in inventory/

## Run playbook for specific version
```console
ansible-playbook upgrade_1_19-1_20.yml
```