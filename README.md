# winserver-hyperv-ad-pme-lab

# Conception d'une Infrastructure Windows Server sous Hyper-V — Active Directory, Réplication, Stockage, WDS et WSUS pour une PME

> Conception et déploiement, dans un environnement virtualisé Hyper-V, d'une infrastructure Windows Server complète pour une PME fictive de 100 employés répartis sur cinq départements : annuaire centralisé, déploiement automatisé des postes, mises à jour centralisées et continuité des données.

**Auteur :** Safae Kanbouh
**Année universitaire :** 2025 – 2026
**Environnement de virtualisation :** Hyper-V

---

## 📖 Description

Une PME ne peut plus se contenter d'une gestion informatique artisanale : postes configurés manuellement, comptes utilisateurs créés au cas par cas, données critiques sans protection en cas de panne. Elle a besoin d'une infrastructure structurée, sécurisée, résiliente et capable d'évoluer avec la croissance de l'organisation.

Ce projet met en scène une entreprise fictive de 100 collaborateurs répartis en cinq départements (Direction, Informatique, Ressources Humaines, Finance, Marketing), utilisée comme cas d'étude pour concevoir, déployer et documenter une infrastructure Windows Server complète et représentative d'un environnement de production, entièrement virtualisée sous Hyper-V.

## 🎯 Objectifs

- Concevoir une architecture Windows Server cohérente pour une PME, avec un plan réseau et un stockage structurés
- Centraliser l'authentification des utilisateurs et des ordinateurs via Active Directory
- Automatiser le déploiement des postes de travail grâce à WDS
- Centraliser les mises à jour de sécurité grâce à WSUS
- Garantir la disponibilité des données critiques par la réplication et des permissions adaptées

## 🛠️ Technologies utilisées

- **Virtualisation :** Hyper-V (Virtual Switches, VHDX, Checkpoints)
- **Annuaire :** Active Directory Domain Services (AD DS), DNS, DHCP
- **Organisation :** Unités d'Organisation (OU) par département, 9 stratégies de groupe (GPO) couvrant sécurité, productivité et conformité
- **Déploiement des postes :** WDS (Windows Deployment Services), PXE, images de démarrage/installation
- **Mises à jour :** WSUS (Windows Server Update Services) — synchronisation, groupes d'ordinateurs, approbation des mises à jour
- **Stockage et continuité :** RAID (0/1/5), réplication Active Directory et SYSVOL (DFSR), sauvegarde et restauration de l'état système
- **Système d'exploitation :** Windows Server 2019
- **Administration avancée :** PowerShell (restauration d'objets Active Directory)
