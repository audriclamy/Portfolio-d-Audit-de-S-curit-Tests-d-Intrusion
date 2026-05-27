# 🛡️ Portfolio d'Audit de Sécurité & Tests d'Intrusion

> *"La meilleure défense naît d'une compréhension profonde de l'attaque."*

---

## 📑 Sommaire
- [👤 À propos de moi](#-à-propos-de-moi)
- [🛠️ Matrice de Compétences Techniques](#️-matrice-de-compétences-techniques)
- [📑 Rapports d'Audit Professionnels](#-rapports-daudit-professionnels)
- [1. Audit d'Infrastructure via Pipeline DevOps](https://github.com/audriclamy/Portfolio-d-Audit-de-S-curit-Tests-d-Intrusion/releases/download/v1.0/Rapport_d_Audit_d_infrastructure_Devops.pdf)
- [2. Audit d'Infrastructure Active Directory ](https://github.com/audriclamy/Portfolio-d-Audit-de-S-curit-Tests-d-Intrusion/releases/download/v1.0/Rapport_d_Audit_de_Securite_Active_Directory.pdf)
- [3. Audit de Sécurité d'Intranet ](https://github.com/audriclamy/Portfolio-d-Audit-de-S-curit-Tests-d-Intrusion/releases/download/v1.0/Rapport_d_Audit_de_Securite_d_intranet.pdf)
- [⚠️ Avertissement Légal & Éthique](#️-avertissement-légal--éthique)

---

## 👤 À propos de moi

Mon parcours professionnel s'est construit sur une conviction profonde : **pour protéger efficacement une infrastructure, il faut d'abord savoir comment elle est construite, du matériel jusqu'à l'applicatif.** Actif dans l'informatique depuis 2013, j'ai forgé mon expérience sur le terrain. De la maintenance réseau en passant par la téléphonie IP et le développement j'ai acquis une vision globale et pragmatique des systèmes d'information. 

Cette polyvalence m'a naturellement conduit vers la cybersécurité lors de mon cursus d'Ingénieur. J'ai eu l'opportunité de concrétiser cette spécialisation au sein de l'équipe Sécurité d'un grand groupe bancaire. Durant cette mission, j'ai piloté l'industrialisation de la sécurité opérationnelle : analyse de vulnérabilités, collecte d’informations, audit des configurations, et automatisation des tâches. Mon objectif a été d'adopter une véritable approche **DevSecOps**, en déployant un tableau de bord automatisés via des conteneurs Docker et des pipelines CI/CD.

Conscient que la défense nécessite une compréhension fine des menaces réelles, j'ai décidé d'explorer le versant offensif. Après l'obtention de mon diplôme, j'ai fait le choix stratégique de me recentrer sur des missions de support et de maintenance matérielle (réparation informatique), me permettant ainsi de garder un ancrage terrain tout en me lançant dans une spécialisation intensive en pentest. J'ai suivi le cursus rigoureux **Penetration Tester de HackTheBox (HTB CPTS)**, me confrontant à des environnements d'entreprise complexes (niveaux Medium et Hard) pour maîtriser les méthodologies d'attaque modernes.

**Aujourd'hui, ce portfolio illustre la synthèse de mon parcours : une approche de l'audit technique guidée par une véritable connaissance des contraintes de production et du terrain.** J'aborde la cybersécurité avec humilité et pragmatisme : face à l'évolution constante des cybermenaces, personne ne détient une science infuse. C'est l'expérience de la production, la capacité d'adaptation et l'amélioration continue qui font la différence. Mon défi quotidien, et la valeur que je souhaite apporter aux entreprises, se résume en trois mots : **accompagner, sécuriser et rassurer.**

---

## 🛠️ Matrice de Compétences Techniques

| Domaine                   | Technologies & Concepts Exploités                                                      |
| :------------------------ | :------------------------------------------------------------------------------------- |
| **Active Directory **     | Abus Kerberos, DCSync, AD CS (ESC8), Mouvements latéraux,  Relais NTLM/Relais kerberos |
| **DevOps**                | Évasion Docker, Compromission de pipelines CI/CD, Jenkins, Git                         |
| **Web & Système (Linux)** | OWASP (XSS, SQLi, Command Injection), Élévation de privilèges                          |
| **Sécurité Défensive**    | Durcissement système, Gestion des vulnérabilités, Analyse de logs                      |

---

## 📑 Rapports d'Audit Professionnels

Voici mes trois rapports détaillant des compromissions complètes d'environnements d'entreprise simulés, allant de la reconnaissance initiale jusqu'à la compromission totale (root/Domain Admin), suivies de recommandations d'atténuation pragmatiques.

### 1. Audit d'Infrastructure DevOps
Analyse des risques et de la surface d'attaque d'une infrastructure d'intégration et de déploiement continus (CI/CD). Le rapport illustre comment des faiblesses de cloisonnement dans les conteneurs et les outils d'automatisation permettent un pivotement direct vers l'hôte physique.
* **Vecteurs clés :** Abus de pipelines Jenkins, Pivot et évasion de conteneur Docker, Exploitation de droits sudo et RSH.
* 📄 [Consulter le Rapport d'Audit DevOps (PDF)](https://github.com/audriclamy/Portfolio-d-Audit-de-S-curit-Tests-d-Intrusion/releases/download/v1.0/Rapport_d_Audit_d_infrastructure_Devops.pdf)

### 3. Audit d'Infrastructure Active Directory 
Évaluation offensive ciblant le cœur d'une infrastructure Windows. Ce rapport met en lumière l'exploitation de défauts de configuration critiques liés aux services de certificats (AD CS) et l'exécution d'attaques de type DCSync menant à la compromission totale du domaine.
* **Vecteurs clés :**  Relais NTLM/Relais kerberos (ESC8), Usurpation d'identité AD, DCSync.
* 📄 [Consulter le Rapport d'Audit AD (PDF)](https://github.com/audriclamy/Portfolio-d-Audit-de-S-curit-Tests-d-Intrusion/releases/download/v1.0/Rapport_d_Audit_de_Securite_Active_Directory.pdf)

### 3. Audit de Sécurité d'Intranet 
Évaluation de la surface applicative d'un portail intranet et du système Linux sous-jacent. L'audit démontre l'enchaînement de vulnérabilités web (OWASP Top 10) menant à une exécution de commande, suivie d'une évasion d'environnement isolé (chroot) par manipulation de privilèges.
* **Vecteurs clés :** Blind SQL Injection (Error-based),Command Injection, Évasion de chroot via PostgreSQL.
* 📄 [Consulter le Rapport d'Audit Intranet (PDF)](https://github.com/audriclamy/Portfolio-d-Audit-de-S-curit-Tests-d-Intrusion/releases/download/v1.0/Rapport_d_Audit_de_Securite_d_intranet.pdf)


---

## ⚠️ Avertissement Légal & Éthique
L'ensemble des techniques, outils et audits présentés dans ce dépôt ont été réalisés exclusivement au sein de laboratoires virtuels d'entraînement (HackTheBox) expressément autorisés, isolés et dédiés à l'apprentissage de la cybersécurité.
