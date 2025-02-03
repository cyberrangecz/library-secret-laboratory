# Cybersecurity game "Secret laboratory"
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-orange.svg)](https://creativecommons.org/licenses/by/4.0/)

Linear game for [CyberRangeCZ Platform](https://docs.platform.cyberrange.cz/) with [APG](https://docs.platform.cyberrange.cz/user-guide-advanced/trainings/trainings-overview/#automatic-generation-problem-apg-in-linear-training-definition).

## Game Levels Summary
- host scan with `nmap`
- exploit `webmin` with `metasploit`
- host exploration and analysis of `.bash_history`
- private SSH key password cracking with `john`
- connection with SSH key and host exploration

## Topology summary
|Host|Image|Flavor|
|-|-|-|
|attacker|kali|standard.small|
|server|debian-12-x86_64|standard.small|
|client|debian-12-x86_64|standard.small|
|router|debian-12-x86_64|standard.small|

## License

This repository uses a dual licensing approach:

* The code (Vagrant, Ansible, and custom code) is licensed under the terms of the MIT License (https://opensource.org/license/mit).
* The game design is licensed under a Creative Commons Attribution 4.0 International License (CC BY 4.0).

**Attribution:**

Based on the game design from:
secret-laboratory (https://gitlab.ics.muni.cz/muni-kypo-trainings/games/secret-laboratory)

**Cybersecurity Laboratory**
Faculty of Informatics
Masaryk University

**Leading authors:** Stanislav Boboň, David Hofman, Jakub Smatana

**Contributors/Consultants:** Valdemar Švábenský, Jan Vykopal
