# development-env

This represents a set of ansible playbooks for provisioning a development box locally

Strongly advised to follow rules on having ansible modules instead of typical shell scripting

Pre-Requisites

- CentOS
- Java based
- Polling Github repos
- At least 4GB of RAM
- 100 GB of storage
- 2 CPUs

Requirements

- OpenJDK 8
- Net-tools
- Vim
- Maven
- Jenkins
- Kafka

For running the playbook, type the below command:

```bash
ansible-playbook main.yml -i development --ask-vault-pass
```

For linting the playbook, type the below command:

```bash
ansible-lint *.yml
```
