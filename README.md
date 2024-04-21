# isa-opdracht2-roles-JasperVanhove

## Files
In de repository bevinden zich volgende bestanden:
- ansible.cfg: Dit bestand gebruik ik om de inventory file van mijn project te specificeren.
- inventory.ini: Dit bestand gebruik ik om de servers te specificeren waarop ik mijn playbooks wil uitvoeren.
- install-odoo.yml: Dit is het playbook die ik gebruik om de Odoo applicatie, met database en reverse proxy, te installeren/configureren.
- roles: Deze map bevat alle nodige roles voor het runnen van het playbook.

## Run
Om het playbook te runnen, voer je volgend commando uit:
```yaml
ansible-playbook install-odoo.yml
```

Ter controle kunnen we via de terminal volgend commando uitvoeren:
```bash
curl http://odoo.network.automation.test/web/login
```