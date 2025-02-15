**Room capacity:** 30 (first-come-first-serve)

Note: 5 seats are reserved for university hosts. So anyone after #25 will be on waiting list.

## Confirmed Participants 
(Please add your name at the **end** of this list if you plan to attend **in-person**, whether presenting or not)
1. Muhammad Usama Sardar
2. Thomas Fossati
3. Ionut Mihalcea
4. Mike Bursell
5. Paul Howard
6. Yogesh Deshpande
7. Jun Zhang
8. Houda Labiod
9. Michael Richardson
10. Ian Oliver 
11. Hannes Tschofenig
12. Guest (from Hannes department)
13. Mathieu Poirier
14. Henk Birkholz
15. Mathias Brossard
16. Thore Sommer
17. Mike Schwartz (maybe)
18. Jean Snyman
19. Anderson Sasaki

## Presentations
Please add your name and topic in the table below if you would like to present) 

| Name  | Title | Relevant material | Specs | Implementation | Duration (min) |
|--|--|--|--|--|--|
| Muhammad Usama Sardar | Formalization of Attested TLS | [Paper](https://www.researchgate.net/publication/385384309_Towards_Validation_of_TLS_13_Formal_Model_and_Vulnerabilities_in_Intel's_RA-TLS_Protocol); [formalization](https://github.com/CCC-Attestation/formal-spec-TEE); [slides etc.](https://github.com/CCC-Attestation/formal-spec-KBS) | [Specs](https://datatracker.ietf.org/doc/draft-fossati-tls-attestation/) | [Implementation](https://github.com/ccc-attestation/attested-tls-poc) | 20|
| Thore Sommer | TPM based Remote Attestation: Pitfalls and Lessons Learned |  |  | [Keylime](https://keylime.dev) | 15 |
| Paul Howard | Endorsement and RV Distribution: Interaction Model, API and Prototyping | [Slides](https://github.com/CCC-Attestation/meetings/blob/main/materials/PaulHoward_EndorsementDistribution_Sept2024.pdf) |  | [Veraison](https://github.com/veraison/services) | 20 |
| Ian Oliver | Forensics and Attestation | abstract[^1] |  |  | 30 + live demo |
| Anderson Sasaki | Expanding Keylime: Attestation for Trusted Execution Environments | [Abstract](https://github.com/ansasaki/fosdem2025-talk-proposal) | [Enhancement Proposal](https://github.com/keylime/enhancements/pull/108) | [Changes to coconut-svsm](https://github.com/coconut-svsm/svsm/pull/528) | 20 |


[^1]: Remote attestation provides us with a demonstration that a given system is in a given state - ideally one where the integrity of the system is according to known good values.
Keeping a history of claims, results and decisions of a system over a longer period of time provides vital information about how a system is evolving over firmware and software changes, as well as potential hardware changes. Utilising this information can provide evidence of unwanted and unexpected changes to a system.
We present here a tool for attestation and forensics, through a simple example. Additionally we provide a case study from a potential firmware CVE and finally provide a case based upon Open Radio Access Network hardware.
