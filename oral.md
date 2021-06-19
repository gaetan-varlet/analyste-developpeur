# Examen d'analyste - oral

- sujets répartis en 2 sous-ensembles : sujets généraux et sujets plus techniques
- le candidat tire au sort un sujet dans chaque sous-ensemble et en choisit un pour préparer l'exposé
- l'exposé vaut la moitié de la note finale, l'autre moitié concerne les réponses aux questions posées
- l'exposé dure 10 minutes et a pour objectif d'apprécier le niveau de connaissance des candidats
- ce qui est évalué dans l'exposé : richesse des connaissances exposées et de leur pertinance, et aussi la clarté de l'exposé
- questions : portent sur les connaissances générales informatiques, sur le rôle de l'analyste, sur les éléments techniques (base de données, langages, architecture, méthodes)
- il y a souvent une question sur un cas pratique qui permet d'apprécier les qualités d'analyse et de logique des candidats
- il faut veiller à parler des points clés, bien structurer ses réponses et être précis dans ses réponses



## Notions importantes

- proxy :
	- machine faisant fonction d'intermédiaire entre un réseau local et internet, il permet de faire des requêtes sur Internet à la place des ordinateurs du réseau local (cache, filtrage, ...)
	- reverse proxy : permet aux utilisateurs d'internet d'accéder à certains serveurs interne (protection contre les attaques directes de l'extérieur, répartiteur de charge...)
- une DMZ (zone démilitarisée) est un sous-réseau séparé du réseau local et isolé de celui-ci et d'Internet (ou d'un autre réseau) par un pare-feu
- les 3 principes de la programmation objet : encapsulation (objet possède propriétés et méthodes) / héritage / polymorphisme
- les AGL (ateliers de génie logiciel) est un logiciel aidant à la réalisation de logiciels : les environnements de conception (Tramis, éditeur de de diagrammes), les environnements de développement (Eclipse, IntelliJ)
- les différents types de bases de données : une BDD est une collection de données stockées de manière ordonnée
	- base de données hiérarchique : premières BDD, organisé sous forme d'arbre, basé sur la relation parent-enfant (un seul parent par enfant)
	- base de données réseau : permettent les relations n-n (plusieurs parents / plusieurs enfants)
	- base de données relationnelle : type de BDD le plus répandu aujourd'hui, basé sur l'algèbre relationnel, organisé en tables
	- base de données NoSQL (not only SQL)  : variété de formats, tels que les clés/valeurs (Redis), les documents (MongoDB), des graphes (Neo4J)..., offre une grande flexibilité et évolutivité
- les 3 référentiels généraux :
	- RGAA (référentiel général d'amélioration de l'accessibilité) : présente les obligations d'une part, et les critères d'autre part pour vérifier la conformité ( critères de niveaux A, AA et AAA, doit valider les 106 critères A et AA)
	- RGS (référentiel général de sécurité) : cadre règlementaire permettant d'instaurer la confiance dans les échanges au sein de l'administration et avec les citoyens
	- RGI (référentiel général d'interopérabilité) : normes et standards qui favorisent l'interopérabilité au sein des systèmes d'information de l'administration
- ANSSI (agence nationale de la sécurité des systèmes d'information) : service du premier ministre, apporte son expertise aux administration et entreprises sur les les opérations d'importance vitale (OIV)
- critères DICP : Disponibilité (accès permanent), Intégrité (données non altérées), Confidentialité (droits/permissions), Preuve (traçabilité)
- MAREVA (méthode d'analyse et de remontée de la valeur) : rentabilité du projet, nécessité de réaliser le projet, risques associées au projet, bénéfices attendus
- RGPD : Règlement général sur la protection des donnée, règlement de l'UE entré en vigueur en 2016
	- encadre le traitement des données personnelles sur le territoire de l’Union européenne
	- une « donnée personnelle » est « toute information se rapportant à une personne physique identifiée ou identifiable »
	- avant le RGPD, système déclaratif à la CNIL (loi de 1978 dite loi informatique et libertés, réglemente la liberté de traitement des données personnelles, c'est-à-dire la liberté de ficher les personnes humaines. Création de l'autorité de contrôle (CNIL))
	- RPGD introduit un **registre des traitements** interne aux administrations/entreprises, ouvert à la CNIL et un **delegué à la protection des données**

## à réviser

- le rôle de l'analyste
- les différents concours du ministère (les différents PSE, Chef de projet...)
- les étapes du projet informatique
- les différents intervenants
- la documentation amont d'un projet informatique
- cycle en V vs agilité (Scrum et Kanban) (et NCS et NCO)
- les différents types de base de données
- les notions de PCA-PRA (plan de continuité / reprise d'activité)
- accessibilité / RGAA (citer au moins une règle)
- loi pour une république numérique
- CNIL et RGPD
- les marchés publics
- sécurité informatique : types d'attaques, référentiels, bonnes pratiques/tests/audits
