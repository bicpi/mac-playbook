# Ansible provision for my MacBooks

1. Install brew
2. Install ansible via brew
3. Run playbook: `ansible-playbook main.yml -i hosts`

To run a specific role only, e.g. the `brew` role:

    ansible-playbook main.yml -i hosts -t brew
