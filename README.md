# Ansible role for deploying ocelot-werker

Available configuraiton options can be seen in `defaults/main.yml`

Need to set at runtime: 
- vault_token
- register_ip

Example playbook run:
```
ansible-playbook -i <inventory-file> -u <username> --key-file <ansible_ssh_key> -e CERTS_DIR=path/to/secrets deploy_consul_cluster.yml
```

| variable | description | required | default |
|----------|-------------|----------|---------|
|          |             |          |         |