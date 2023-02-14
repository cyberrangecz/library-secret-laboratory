# Cybersecurity game "Secret laboratory"

Linear game for [KYPO CRP](https://docs.crp.kypo.muni.cz/) with [APG](https://docs.crp.kypo.muni.cz/user-guide-advanced/trainings/trainings-overview/#automatic-generation-problem-apg-in-linear-training-definition).

## Game Levels Summary
- host scan with `nmap`
- exploit `webmin` with `metasploit`
- host exploration and analysis of `.bash_history`
- private SSH key password cracking with `john`
- connection with SSH key and host exploration

## Topology summary
|Host|Image|Flavor|
|-|-|-|
|attacker|kali|csirtmu.tiny1x2|
|server|debian-10|csirtmu.tiny1x2|
|client|debian-10|csirtmu.tiny1x2|
|router|debian-10-x86_64|csirtmu.tiny1x2|

## License and Credits
See [licensing](https://gitlab.ics.muni.cz/muni-kypo-trainings/games/all-games-index#license) and how to [cite it](https://gitlab.ics.muni.cz/muni-kypo-trainings/games/all-games-index#how-to-cite-the-games).

[Cybersecurity Laboratory](https://cybersec.fi.muni.cz)\
Faculty of Informatics\
Masaryk University

**Leading authors:** Stanislav Boboň, David Hofman, Jakub Smatana

**Contributors/Consultants:** Valdemar Švábenský, Jan Vykopal
