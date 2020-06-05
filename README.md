# Docker Lab Ansible
### Projeto: Criar ambiente de Lab Ansible

Este projeto consiste em criar três containers para Lab de uso do **Ansible**. Iremos usar o Docker Compose para automatizar a criação dos containers.

### Estrutura
Ambiente consiste em criar três containers para um deles ser usado para instalar e configurar o Lab de automação de processos.
- 172.28.1.10 SRV-ANSIBLE
- 172.28.1.11 SRV-HOST01
- 172.28.1.12 SRV-HOST02

### Comandos
```
# docker-compose up -d

# ssh root@172.28.1.10
```