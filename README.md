# investigation
Rapports d'investigations

*  Identifier et analyser les traces laissées lors de l'instruction dans un système informatique
* Collecter correctement les preuves nécessaires à des poursuites judiciaires
* Collecter et analyser des informations à des fins d'investigation
* Contourner les protections : pas uniquement de l'analyse finalement
* Suivi (tracking)
* Retrouver les traces : personnes ou journaux
* Trouver les traces cachées


# Résumé : Les différentes parties de l'investigation numérique

L'investigation numérique est un processus structuré qui permet de **retrouver, analyser et exploiter des traces numériques** dans le cadre d’un incident de sécurité, d’une fraude, ou d’une enquête judiciaire.

---

## 1. Identification

**Objectif** : Détecter qu’un incident s’est produit et identifier les sources potentielles de preuves.

**Actions clés** :
- Surveillance des journaux systèmes
- Alertes de sécurité (SIEM, IDS/IPS)
- Rapports d’utilisateurs

---

## 2. Préservation (ou acquisition)

**Objectif** : Sauvegarder les données sans les altérer, pour garantir leur intégrité.

**Actions clés** :
- Création d’images disques (bit à bit)
- Blocage de l’écriture (write blocker)
- Chaîne de traçabilité (chain of custody)

---

## 3. Analyse

**Objectif** : Examiner en profondeur les données collectées pour extraire les éléments pertinents.

**Types d’analyse** :
- Analyse des fichiers journaux (logs)
- Recherche de malwares ou de backdoors
- Extraction de métadonnées
- Analyse réseau (PCAP)

---

## 4. Documentation

**Objectif** : Noter précisément chaque étape pour assurer la reproductibilité et la validité judiciaire.

**Bonnes pratiques** :
- Horodatage de chaque action
- Captures d’écran
- Rapport structuré

---

## 5. Présentation

**Objectif** : Présenter les résultats de l’analyse à des décideurs, enquêteurs ou en justice.

**Supports possibles** :
- Rapports techniques
- Synthèses visuelles
- Témoignage en cour

---

##  6. Contournement / Réponse active

**Objectif** : Dans certains contextes offensifs ou défensifs, il faut aussi comprendre comment les protections ont été contournées.

**Actions associées** :
- Analyse de rootkits ou techniques d’évasion
- Reconstruction des vecteurs d’attaque

---

## 7. Retrouver les traces

**Objectif** : Identifier les activités passées malgré des tentatives de suppression.

**Exemples** :
- Récupération de fichiers supprimés
- Historique des connexions
- Restauration d’artefacts

---

## 8. Recherche des traces cachées

**Objectif** : Détecter des preuves dissimulées volontairement.

**Techniques** :
- Analyse de stéganographie
- Recherche dans les espaces non alloués
- Analyse des time stamps anormaux

---

> **Note** : Chaque étape doit être menée avec rigueur et traçabilité, notamment dans un cadre judiciaire.




