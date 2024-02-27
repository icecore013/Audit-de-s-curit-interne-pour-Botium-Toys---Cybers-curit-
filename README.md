# Botium Toys - Audit de sécurité interne

Ce projet consiste en un audit de sécurité interne pour Botium Toys, une entreprise de jouets fictive. L'objectif principal de cet audit est d'identifier les risques et les vulnérabilités dans le système informatique de l'entreprise et de proposer des mesures de sécurité pour atténuer ces risques.

## Portée et objectifs de l'audit

La portée de l'audit couvre l'ensemble du programme de sécurité de Botium Toys, y compris toutes les ressources numériques, les processus et procédures internes. Les objectifs de l'audit sont les suivants :

1. Adhérer au cadre de cybersécurité du NIST CSF.
2. Mettre en place de meilleurs processus pour les systèmes.
3. Renforcer les contrôles du système.
4. Implémenter le concept des moindres autorisations dans le cadre de la gestion des informations d'identification des utilisateurs.
5. Établir leurs politiques et procédures, y compris leurs playbooks.
6. Veiller à ce qu'ils respectent les exigences en matière de conformité.

Pour plus de détails, consultez le document suivant : [Portfolio-Activity-Conduct-a-security-audit-Part-1_Botium-Toys_-Audit-scope-and-goals.docx](Portfolio-Activity-Conduct-a-security-audit-Part-1_Botium-Toys_-Audit-scope-and-goals.docx)

## Évaluation des risques

J'ai effectué une évaluation des risques pour Botium Toys afin d'identifier les risques potentiels et de déterminer leur impact sur l'entreprise. L'évaluation a révélé un score de risque actuel de 8 sur une échelle de 1 à 10.

Pour plus de détails sur l'évaluation des risques, consultez le document suivant : [Portfolio-Activity-Conduct-a-security-audit-Part-1_Botium-Toys_-Risk-assessment.docx](Portfolio-Activity-Conduct-a-security-audit-Part-1_Botium-Toys_-Risk-assessment.docx)

## Évaluation des contrôles

J'ai évalué les contrôles existants et sélectionné ceux qui doivent être mis en œuvre pour atténuer les risques identifiés. Voici les contrôles sélectionnés et leur priorité :

### Contrôles administratifs

| Nom du contrôle | Type de contrôle et explication | Doit être mis en œuvre (X) | Priorité |
| --- | --- | --- | --- |
| Moindre privilège | Préventif ; réduit les risques en s'assurant que les vendeurs et le personnel non autorisé n'ont accès qu'aux ressources informatiques/données dont ils ont besoin pour faire leur travail | X | Élevée |
| Plans de reprise après sinistre | Correctif ; continuité des activités pour s'assurer que les systèmes peuvent fonctionner en cas d'incident/qu'il y a une perte de productivité limitée ou nulle due aux temps d'arrêt/un faible impact sur les composants du système | X | Élevée |
| Politiques de mots de passe | Préventif ; établir des règles sur la force des mots de passe pour améliorer la sécurité/réduire la probabilité de compromission des comptes par des techniques d'attaque par force brute ou par dictionnaire | X | Élevée |
| Politiques de contrôle d'accès | Préventif ; renforcer la confidentialité et l'intégrité des données | X | Élevée |
| Politiques de gestion des comptes | Préventif ; réduire la surface d'attaque et limiter l'impact global des employés mécontents/anciens employés | X | Élevée |
| Séparation des tâches | Préventif ; veiller à ce que personne ne dispose d'un accès qui pourrait lui permettre d'abuser du système à des fins personnelles | X | Moyenne |

### Contrôles techniques

| Nom du contrôle | Type de contrôle et explication | Doit être mis en œuvre (X) | Priorité |
| --- | --- | --- | --- |
| Pare-feu | Préventif , des pare-feux sont déjà en place pour filtrer le trafic indésirable/malveillant qui pénètre dans le réseau interne |  | Moyenne |
| Système de détection d'intrusion (IDS) | Détectif ; permet à l'équipe informatique d'identifier rapidement d'éventuelles intrusions (par exemple, un trafic anormal) | X | Élevée |
| Chiffrement | Dissuasif ; rend les informations/données confidentielles plus sûres (par exemple, les transactions de paiement sur des sites web) | X | Élevée |
| Sauvegardes | Correctif ; permet de maintenir la productivité en cas d'événement ; s'aligne sur le plan de reprise après sinistre | X | Élevée |
| Système de gestion des mots de passe | Correctif ; récupération des mots de passe, réinitialisation, notifications de verrouillage | X | Moyenne |
| Logiciel antivirus (AV) | Correctif ; détecter et mettre en quarantaine les menaces connues | X | Élevée |
| Surveillance, maintenance et intervention manuelles | Préventif/correctif ; requis pour les systèmes existants afin d'identifier et d'atténuer les menaces, les risques et les vulnérabilités potentiels | X | Élevée |

Pour plus de détails sur l'évaluation des contrôles, consultez le document suivant : [Botium Toys _Portfolio-Activity-Conduct-a-security-audit.docx](Botium Toys _Portfolio-Activity-Conduct-a-security-audit.docx)

En conclusion, cet audit de sécurité interne a permis d'identifier les risques et les vulnérabilités du système informatique de Botium Toys et de proposer des mesures de sécurité pour les atténuer. Les résultats de cet audit aideront Botium Toys à améliorer sa posture de sécurité globale et à se conformer aux réglementations applicables.
