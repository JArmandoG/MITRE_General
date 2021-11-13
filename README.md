# MITRE_Misc

# CAR - CYBER ANALYTICS REPOSITORY

---

[Analytics](https://car.mitre.org/analytics/)

Scripts enfocados a Sysmon, Osquery → Splunk, etc. para detección de Tácticas y Técnicas

# MITRE ATT&CK

---

[An exercise](Exercise_1.md)

### General Info:

**Tactic vs. Technique vs. Procedure:**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3dec05d4-6cce-467c-b9d0-6944af68283f/Untitled.png)

*"Atomic Indicator": IP address, File Hash, etc. (Indicadores mínimos de presencia de un adversario)*

**Usage**: Incident Report / Observable Behavior → Mapping to MITRE ATT&CK

Recommendations:

- UNDERSTAND ATT&CK
- FIND BEHAVIOR
- RESEARCH BEHAVIOR
- TRANSLATE THE BEHAVIOR → TACTIC
- WHICH TECHNIQUES APPLIES TO THE BEHAVIOR
- COMPARE RESULTS

## General resources

Pdf: Getting started with ATT&CK (GOOD)

[](https://www.mitre.org/sites/default/files/publications/mitre-getting-started-with-attack-october-2019.pdf)

### PDF: Foundations of Operationalizing MITRE ATT&CK

[](https://academy.attackiq.com/learn/topicGroups/232eea9f-1b5a-44a7-b58b-83cd705de2f3/download?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJxdWVyeSI6eyJ0b3BpY0dyb3VwSWQiOiIzOGY4NmI0NS04MTUxLTQ2NmYtYTQxNi0yYmIwNjUxMGE2MDkiLCJjYXRlZ29yeUluZGV4IjoiMCIsInN1YmNhdGVnb3J5SW5kZXgiOiIwIiwiZmlsZUluZGV4IjoiMCIsImRvd25sb2FkIjoiIn0sImNvdXJzZUlkIjoiMjMyZWVhOWYtMWI1YS00NGE3LWI1OGItODNjZDcwNWRlMmYzIiwiaWF0IjoxNjM0MDAxOTY2LCJleHAiOjE2MzQwMDIyNjZ9.Ndsu2fJsOXQIqvKWYsEuC8O8RNr0Nrr1n6SXf6UlDCg)

**MITRE ATT&CK FOR DUMMIES PDF**

[](https://attackiq.com/wp-content/uploads/2020/12/9781119748106.pdf)

**MITRE ATT&CK GROUPS**

[Groups](https://attack.mitre.org/groups/)

[CISA_Best_Practices_for_MITRE_ATTCK_Mapping_.pdf](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/42d43062-2a59-4df5-ae76-9e1763472ea4/CISA_Best_Practices_for_MITRE_ATTCK_Mapping_.pdf)

## MATRIX - USAGE

---

### MATRIX & GROUPS -

[Enterprise Matrix](https://attack.mitre.org/matrices/enterprise/)

[Groups](https://attack.mitre.org/groups/)

### BY INDUSTRY -

Example: Searching for ecommerce industry:

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b286f28c-db30-49a3-9f65-768a73804e92/Untitled.png)

## NAVIGATOR

[ATT&CK® Navigator](https://mitre-attack.github.io/attack-navigator/)

Use the Navigator directly for a custom Matrix or select it from APT Group, technique, or even Software (i.e. Mimikatz) and see the Matrix already highlighted for the tactic, technique, group or swoftware:

### Example usage

![Directly into a Navigator highlighting this group's tactics & techniques](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d293fef5-c103-4954-9201-474e5547af89/Untitled.png)

Directly into a Navigator highlighting this group's tactics & techniques

**Ejemplo: Conti (Software)**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f5bf621d-0d75-4fc3-a805-9deb8212db5f/Untitled.png)

## Red Team Simulators:

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0fd783d7-f386-45ae-b8cb-c6f203d0701b/Untitled.png)

### Breach and Attack Simulations (BAS) Technologies

[](https://medium.com/@george.fekkas/breach-and-attack-simulation-bas-technologies-10e2777ee5af)

# MITRE CAR (Cyber Analytics Repository)

[Analytics](https://car.mitre.org/analytics)

[attack-scripts/scripts at master · mitre-attack/attack-scripts](https://github.com/mitre-attack/attack-scripts/tree/master/scripts)

Attack scripts

Usage (Extract logs → Integrate a SIEM → Use Datasets for testing → Analyze with MITRE CAR)

- Use SIGMA for translating CAR analytics into other languages

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/49a2f49f-ae06-4786-9d94-c98aefd8c5fc/Untitled.png)

# MITRE D3FENSE

[]()
