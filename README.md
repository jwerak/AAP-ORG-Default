# AAP Org repository

Toto je repozitář pro demonstraci nastavení Ansible Automatizační platformy (AAP) a organizaci automatizace do repozitářů podle účelu.
Pro nastavení AAP bude využita kolekce [redhat_cop.controller_configuration](https://github.com/redhat-cop/controller_configuration).

### Druhy repozitářů a jmenné konvence

| Prefix   | Účel                                                                                                                                   |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| AAP-ORG- | konfigurace [Organizace](https://docs.ansible.com/automation-controller/latest/html/userguide/organizations.html) v Ansible Controller |
| AAP-COL- | [Ansible kolekce](https://docs.ansible.com/ansible/latest/dev_guide/developing_collections.html)                                       |
| AAP-PRJ- | Projekt v Ansible Controller s ansible playbooky                                                                                       |
| AAP-INV- | Inventory jako jednoduchá náhrada za CMDB                                                                                              |
| AAP-EE-  | Definice [Execution Environment](https://docs.ansible.com/automation-controller/latest/html/userguide/execution_environments.html)     |

## Odkazy na použité repozitáře

Tato organizace bude využívat tyto repozitáře:

| Repozitář                                                          | Účel                                                          |
| ------------------------------------------------------------------ | ------------------------------------------------------------- |
| [AAP-ORG-Default](https://github.com/jwerak/AAP-ORG-Default)       | konfigurace Default Organizace v Ansible Controller           |
| [AAP-COL-networking](https://github.com/jwerak/AAP-COL-networking) | kolekce obshahující konfiguraci sítí                          |
| [AAP-PRJ-vm](https://github.com/jwerak/AAP-PRJ-vm)                 | Projekt obshahující VM akce - create/start/stop/snapshot, atd |
| [AAP-PRJ-network](https://github.com/jwerak/AAP-PRJ-network)       | Projekt obshahující akce na konfiguraci sítí                  |
| [AAP-PRJ-linux](https://github.com/jwerak/AAP-PRJ-linux)           | Projekt obshahující akce na konfigurace Linux OS              |
| [AAP-INV-linux](https://github.com/jwerak/AAP-INV-linux)           | Inventory VM                                                  |
| [AAP-EE-main](https://github.com/jwerak/AAP-EE-main)               | Execution Environment                                         |
