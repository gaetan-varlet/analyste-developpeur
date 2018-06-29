# Examen d'analyste - écrit

## **Introduction**
- phrase de contexte
- limite de l'existant / objectif de l'application
- champ / hors champ
- Ce dossier est en phase d'analyse. Les diagrammes joints en annexe de ce dossier sont réalisés à l'aide du langage de modélisation orienté objet **UML** (Unified Modeling Language)
- L'étude se présente de la façon suivante :
  - une première partie pour la note fonctionnelle (question 1)
  - une seconde partie présente l'architecture technique (question 3)
  - une troisième partie ...
- Le dossier s'appuie également sur les annexes suivantes :
  - Annexe 1 : Diagramme des cas d'utilisation (question 1)
  - Anexxe 2 : Diagramme de classes (question 2)

## Question 1 : **Note fonctionnelle** / note de synthèse
- environ 6 pages avec **un diagramme de cas d'utilisation** (Qui ? Quand ? Pourquoi ? Comment ?)
- environ 5-7 points
- intro
  - présentation des grandes fonctionnalités regroupant les CU décrit dans le diagramme des cas d'utilisation
  - présentation des acteurs
    - point sur les habilitations : sauf mention contraire, il est supposé par la suite que ces acteurs se sont authentifiés auprès de l'application par la saisie d'un identifiant et d'un mot de passe
- présentation des CU regroupés en grandes fonctionnalités
- conclusion avec ouverture sur des perspectives futures :
  - cette solution, sur le plan fonctionnel et organisationnel, permet de répondre aux besoins
  - la note repose également sur une modélisation des données schématisée dans le diagramme de classe en annexe
  - évolutions possibles
  - transition pour la note d'architecture : cette solution présehtée ici sur le plan fonctionnel, devra s'asseoir sur une architecture applicative, technique (ou logicielle) et matérielle (ou physique) dont la description complète est fournie ci-après

## Question 2 : **diagramme de classe**
- environ 4 points
- cohérence acec la description en Q1
- juste les champs dans les classes, cardinalités, associations
- dictionnaire des classes et des associations

## Question 3 : **Note d'architecture**, doit être conforme au schéma directeur
- intro : suite à la spécification fonctionnelle, il convient de proposer une solution sur le plan technique répondant aux besoins
- **architecture applicative** :
  - choix de l'architecture applicative : maître/esclave, monoposte, client/serveur, client/serveur web etc...
  - on choisit une architecture de type client serveur web car
    - répond au besoin d'accès distant
    - répond à tous les besoins de la note fonctionnelle
    - technologie stable, mature, et largement documentée
  - détermination des services
    - archi client serveur-web facilite la construction de l'application en services
    - il existe en général un service métier par cas d'utilisation
    - services techniques : service d'authentification, service d'impression, service de contrôle de formulaire, service de présentation de pages web..0
- **architecture logicielle** :
  - serveur web Apache, serveur d'application Tomcat, SGBDR PostgreSql, openldap pour l'authentification, DMZ pour l'ouverture au grand public
  - les composants de communications : présentation réalisée avec un serveur Web Apache, client léger de type navigateur web
  - les composants spécifiques liés aux traitements : Java EE serveur d'application Tomcat, JDBC pour l'accès aux données depuis Tomcat, langage SQL pour les requêtes
  - les données : base de données relationnelle PostgreSql
  - authentification réalisée avec un annuaire de type LDAP comme openldap
- **architecture physique** :
  - le réseau : protocole TCP/IP sur le réseaux local LAN et l'accès à distance au réseau local WAN avec une connexion internet de type ADSL
    - accès à distance en utilisant un VPN pour avoir une connexion sécurisée : interconnexion de réseaux locaux via une technique de tunnel sécurisé
  - les serveurs : serveurs Linux de type x86
  - serveur web Apache sera installé en DMZ protégé par des pare-feu si le site est accessible sur internet
  - les postes de travail : Windows ou Linux avec navigateur web
- conclusion : ces choix applicatifs, logiciels et matériels permettent de répondre aux besoins exprimés en première partie + évol possible

## Autre question : **Diagramme d'activité**
- penser à le commenter

## Autre question : **Maquettes d'écran**
- charte graphique
- logo institutionnel en haut à gauche
- retour à l'accueil
- bouton de déconnexion
- décrire l'écran
