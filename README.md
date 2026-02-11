# 🖥️ Mise en place d’une infrastructure réseau sous Linux

## 📌 Contexte
Ce projet a été réalisé dans le cadre de ma Licence 3 Réseaux, Systèmes et Sécurité à Supdeco.  
L’objectif était de concevoir et déployer une infrastructure réseau interne pour l’entreprise  **KaneProTechnology**, avec des services essentiels pour plusieurs départements.

---

## 🎯 Objectifs
- Fournir un réseau interne fonctionnel et sécurisé
- Mettre en place des services réseau essentiels
- Gérer les droits d’accès par département
- Documenter toutes les configurations et tests

---

## 🛠️ Technologies utilisées
- **OS Serveur** : Ubuntu Server 22.04 LTS  
- **Services** :
  - DHCP : attribution dynamique d’adresses IP
  - DNS : résolution des noms internes (`kaneprotechnology.sn`)
  - Apache2 : hébergement de 3 sites web (IT, RH, Commercial)
  - Samba : partage de fichiers en lecture seule
  - FTP/FTPS : accès avec authentification par groupe

---

## 📷 Captures d’écran
Les captures détaillées sont disponibles dans le dossier [`captures/`](captures/).

---

## 📚 Rapport du projet
📄 [Télécharger le rapport PowerPoint](Rapport-projet.pptx)  
📄 [Télécharger le rapport PDF](rapport-infrastructure-linux.pdf)

---

## 📚 Résultats
- Attribution dynamique d’IP fonctionnelle
- Résolution DNS interne opérationnelle
- Sites web accessibles depuis tous les clients
- Partages Samba et FTP sécurisés avec droits spécifiques

---

## 🚀 Améliorations possibles
- Ajout d’un pare-feu (pfSense)
- Monitoring des services (Zabbix)
- Automatisation des sauvegardes

---

📌 **Auteur** : Mouhamadou LEYE – Licence 3 Réseaux, Systèmes et Sécurité – Supdeco Dakar
