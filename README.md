# Trailhead

Ansible playbook to setup traefik

## TODO

- http to https redirect
- ssl cert signing and automated renewal
- sticky sessions?
- health checks
- hardcoded routes, services, etc to ansible vars
- documentation

## Useful commands

- `ansible all -m ping -i hosts.yml -u ubuntu`
- `ansible-playbook -i hosts.yml playbook.yml -u ubuntu`
