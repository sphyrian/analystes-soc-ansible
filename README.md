## Formation Ansible (2021-01-26)

Pour synchroniser les rôles:
```
ansible-galaxy install -r requirements.yml -p roles
```

Utilisation d'un playbook avec une variable chiffrée
```
ansible-playbook playbook-add-bob.yml --vault-id=vault.data
```
