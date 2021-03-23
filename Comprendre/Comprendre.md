# Comprendre

Essayez de synthétiser en binôme votre compréhension de la notion que vous avez vue (s'il s'agissait de plusieurs notions, vous pouvez répéter ce paragraphe plusieurs fois) : 

# Bases de données relationnelles

# Quel est son rôle ? 
Elles permettent de structurer des données de manière à ce que ces dernières soient aisément et rapidement consultées, rangées en lignes/colonnes et/ou modifiées.

# Quel est son intérêt ? 
Les SGBD relationnels mettent au premier plan les relations entre les données. 

# A-t-elle des désavantages ? 
C'est extrêment formaté et il existe de fortes conventions à respecter. 

# Y a-t-il plusieurs façons de s'en servir ? 
Plusieurs choix : faire une requête SQL via un fichier PHP, le terminal ou une application Web de gestion pour les systèmes de gestion de base de données (phpMyAdmin).

# Quelles sont les étapes importantes pour la mettre en place ? 
Découper la création de la base de données en deux étapes : 
a) conception (modèle conceptuel "entité-association" > relationnel > conceptuel > logique > physique)
b) exploitation (ajout, suppression, modification des données à travers un langage de requête : SQL)

# Quelles sont les nuances d'un langage à l'autre ? 
/ 

# Existe-t-il des contextes (langages, environnements, outils) où elle n'existe pas ? 
/ 

# Quelles sont ses alternatives ? 
NoSQL 

# <u>Terminologie</u>

## Entité :
Toute famille d'objets similaires présents dans une base de donnée.

## Association :
Elle fait le lien entre plusieurs entités (au moins deux) et souvent représenté par un verbe d'action. 

## Relation :
Le lien entre les tables correspond à une relation. 

## Clé primaire VS étrangère
- les clés primaires servent à identifier une ligne de manière unique ;
- les clés étrangères permettent de gérer des relations entre plusieurs tables, et garantissent la cohérence des données.

## Cardinalité :
Cela fait référence aux relations qu'une table a avec une autre (N-N, 1-N).

## Jointure :
C'est un moyen de travailler avec plusieurs tables à la fois afin de mieux découper les informations, d'éviter des répétitions et de rendre ainsi les données plus faciles à gérer.

## Normalisation :
C'est une approche systématique pour décomposer une table conséquente en plusieurs tables moindres ; ce qui éviterait la redondance et des anomalies liées à l'insertion ou à la mise à jour de données. 

## CRUD :
Acronyme signifiant Create, Read, Update, Delete
= méthode d'organisation des données.