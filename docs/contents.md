| [Home](https://github.com/fortinet-fortisoar/solution-pack-mitre-attack-enrichment-framework/blob/release/2.0.3/README.md) |
|----------------------------------------------------------------------------------------------------------------------------|

# Contents

## Connector

| Name              | Description                                                                                                                                              |
|:------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------|
| MITRE ATT&CK&reg; | Helps replicate knowledge base of adversary tactics and techniques based on real-world observations as described in the MITRE ATT&CK&reg; knowledge base |

>**Warning:** After deployment, this Solution Pack installs or upgrades the connector to the latest version.

## Modules

| Name           | Description                                                                                                                                                                                                                                                                |
|:---------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Groups         | This module captures and displays information related to similar intrusion activities tracked by a common name in the security community.                                                                                                                                  |
| Mitigation     | This module creates records of security concepts and classes of technologies that can be used to prevent a technique or sub-technique from being successfully executed.                                                                                                    |
| Software       | This module creates records of custom or commercial code, operating system utilities, open-source software, or other tools used to conduct behavior modeled in ATT&CK.                                                                                                     |
| Techniques     | This module creates records that represent *how* an adversary achieves a tactical goal by performing an action. E.g. *Abuse Elevation Control Mechanism* is a set of circumventing mechanisms designed to control elevate privileges for gaining higher-level permissions. |
| Sub-techniques | Sub-techniques are smaller actions used by an adversary to achieve the larger result targeted by a particular technique. For example, *Abuse Elevation Control Mechanism* is technique that requires a sub-technique of bypassing User Account Control                     |
| Tactics        | Tactics represent the *why* of an ATT&CK technique or sub-technique. For example, in the tactic *Reconnaissance*, the adversary tries to gather information they can use to plan future operations.                                                                        |

## Role

| Role                 | Description                                                                       |
|:---------------------|:----------------------------------------------------------------------------------|
| Full App Permissions | Create, Read, Update and Delete permissions for Scans and Vulnerabilities modules |
| Mitre Admin          | Create, Read, Update and Delete permissions for MITRE ATT&CK&reg; modules         |

## View Template

- MITRE ATT&CK

## Playbook Collection<sup>NEW</sup>

| 10 - SP - MITRE ATT&CK&reg; Enrichment Framework<sup>NEW</sup> |
|:----------------------------------------------------------|

| Playbook Name                                               | Description                                                                                              |
|:------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------|
| Link ATT&CK Technique to Alert (On Create)<sup>NEW</sup>    | Links MITRE technique or sub-technique to an alert, when a Technique ID is added                 |
| Link ATT&CK Technique to Alert (On Update)<sup>NEW</sup>    | Links MITRE technique or sub-technique to an alert, when a Technique ID is updated or changed    |
| Link ATT&CK Technique to Incident (On Create)<sup>NEW</sup> | Links MITRE technique or sub-technique to an incident, when a Technique ID is added              |
| Link ATT&CK Technique to Incident (On Update)<sup>NEW</sup> | Links MITRE technique or sub-technique to an incident, when a Technique ID is updated or changed |