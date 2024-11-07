#TPI-Lucie
Ce projet sers à l'automatisation d'installation de certaines applications via les scripts Ansible.
Il est réalisé dans le cadre de mon TPI à l'EPFL.
## Prérequis

Avant d'utiliser ces playbooks, assurez-vous que vous avez les éléments suivants :

- **Ansible** installé sur votre machine locale (ou sur une machine de gestion).
  - Si Ansible n'est pas installé, vous pouvez l'installer en suivant les instructions de la [documentation officielle d'Ansible](https://docs.ansible.com/ansible/latest/installation_guide/).
  
- **Accès SSH** aux serveurs cibles avec un utilisateur ayant les privilèges nécessaires pour exécuter des tâches avec **sudo**.

- Les serveurs cibles doivent être sous **Ubuntu 22.04** ou **Ubuntu 24.04** pour les playbooks actuels.

## Installation

1. Clonez ce repository dans votre répertoire local :
   ```bash
   git clone https://github.com/votre-utilisateur/playbooks-ansible.git
   cd playbooks-ansible
## Lancer un playbook
Pour lancer un playbook, il vous faut utiliser la commande ansible-playbook -i inventory.ini nom_playbook.yml
