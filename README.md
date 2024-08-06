# Pire2pireUML

Bienvenue dans le dépôt du projet Pire2Pire. Ce projet implique l'organisation de formations éducatifs en modules, la gestion de la progression des apprenants.
Vous pouvez trouvez la conception de la BDD avec la méthodologie MERISE dans le dépôt suivant : [Pire2pireMerise](https://github.com/ValerieRas/Pire2pire)

# Sommaire 

1. [Definition UML](#definition-merise) 
2. [Contexte du Projet](#contexte-du-projet)
3. [Livrables](#livrables)
4. [UML](UML/)
    - [Diagramme de cas d'utilisation](UML/use-case.md)
    - [Diagramme d'activité](UML/activity-diagram.md)
    - [Diagrammes de séquence](UML/sequence-diagrams.md)
    - [Diagramme de de classe](UML/class-diagram.md)
5. [Règles de Gestion](Doc/management_rules.md)


# Definition UML

L'UML, c’est le langage de modélisation unifié. Il permet de créer des diagrammes pour représenter visuellement les aspects d’un système, comme sa structure et ses interactions. C’est un outil pratique pour planifier et concevoir des logiciels.


# Contexte du projet

Les formations sont organisés en modules.

Chaque module est caractérisé par un numéro de module sous forme de Semantic Versionning, un intitulé, un objectif pédagogique, un contenu (textes, images et vidéos), une durée en heures, un ou plusieurs tags et un auteur.

Un module peut faire partie d'une ou plusieurs formations, comme par exemple un pire module "Commandes de base Git" pourrait faire partie d'une pire formation "Frontend Javascript" et "DevOps", voir  plus.

Un module peut contenir un texte et/ou une image et/ou une vidéo.

Les apprenants peuvent s'inscrire à une ou plusieurs formations, ils peuvent choisir de ne pas suivre certains des modules s'ils possèdent déjà, par exemple, les compétences. Autrement dit, ils peuvent arbitrairement valider les modules de leur choix en un clic.

Chaque apprenant est évalué pour chaque module et possède un état de fin de module (OK / KO).

Une formation est considérée comme terminée lorsque tous les modules ont été validés.

Chaque apprenant est caractérisé par un numéro d’inscription unique, un nom, un prénom, une adresse et une date de naissance.

Un ou plusieurs formateurs est auteur d'un module pour une formation donnée, chaque formateur est caractérisé par un code, un nom, un prénom.


# Livrables

- Un dépôt Github recensant : 
    - Un README explicite et soigné
    - Un diagramme de classes UML
    - Au moins deux diagrammes de séquence UML différents
    - Un diagramme de cas d'utilisation UML
    - Un diagramme d'activité UML
    - Un document expliquant les choix de conception
