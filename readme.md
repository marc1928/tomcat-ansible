# Projet Ansible : Déploiement de Tomcat et d'une application

Ce projet vise à automatiser le déploiement et la configuration d'un serveur Tomcat à l'aide d'Ansible. Il inclut la gestion des variables, l'utilisation de templates, l'installation depuis la source, et le déploiement d'une application.

## Objectifs

1. **Création d'un playbook Ansible** :
    - Structurer les variables pour les inventaires.
    - Utiliser des templates pour les fichiers de configuration.
    - Installer Tomcat à partir de la source.
    - Déployer une application sur le serveur Tomcat.
    - Configurer la JVM avec les paramètres suivants :
      - Mémoire minimale : 225 Mo
      - Mémoire maximale : 256 Mo

2. **Réorganisation en rôles Ansible** :
    - Refactoriser le playbook pour le structurer en rôles Ansible, facilitant la réutilisation et la maintenance.

## Structure du Projet

- **Inventaires** : Gestion des variables pour différents environnements.
- **Templates** : Fichiers de configuration dynamiques pour Tomcat.
- **Rôles** : Organisation modulaire des tâches Ansible.

## Prérequis

- Ansible installé sur votre machine.
- Accès à un serveur cible pour le déploiement.
- Droits administratifs sur le serveur cible.

## Instructions

1. Clonez ce dépôt sur votre machine locale.
2. Modifiez les fichiers d'inventaire pour correspondre à votre environnement.
3. Exécutez le playbook principal pour déployer Tomcat et l'application.

## Ressources

- [Documentation Ansible](https://docs.ansible.com/)
- [Site officiel de Tomcat](https://tomcat.apache.org/)

## Auteur

Ce projet a été conçu pour automatiser et simplifier le déploiement de Tomcat en production.


  - name: installation de tomcat  via la source 
    
    - name: création du user admin et gestionnaire de tomcat
    
    - name: Activationde l'accès à distance de tomcat 
    
    - name: déployer une apllication sur le server 
    
    - name: Modification des paramètres de la JVM 