# Gestion des Étudiants avec Spring Boot
Ce projet consiste à développer une application CRUD en Java avec Spring Boot, permettant de gérer les informations des étudiants via une API REST. L'application utilise une base de données MySQL et offre une interface de documentation avec Swagger UI.

## Prérequis
JDK 17 ou plus récent
IDE compatible avec Maven (ex : IntelliJ IDEA)
MySQL Server
Maven pour la gestion des dépendances
JDBC MySQL Driver (mysql-connector-java)

## Structure du Projet :
Le projet suit une architecture en couches :
Composants principaux :
com.example.student_management.entities: Contient l'entité Student représentant un étudiant.
com.example.student_management.repositories: Contient les interfaces de dépôt (Repository) pour les opérations CRUD.
com.example.student_management.services: Contient la logique métier (Services).
com.example.student_management.controllers: Contient les contrôleurs REST pour gérer les requêtes HTTP.
StudentManagementApplication.java: La classe principale de l'application.

## Fonctionnalités Implémentées :

Ajouter un étudiant avec des informations spécifiques.
Supprimer un étudiant.
Récupérer tous les étudiants ou un nombre total.
Compter les étudiants par année de naissance.
## Instructions :
Configuration MySQL :

Créez une base de données MySQL nommée studentdb.
Modifiez les paramètres de connexion dans le fichier application.properties.
Exécution du projet :

Clonez le projet depuis GitHub.
Allez dans le répertoire student-management.
Exécutez le projet avec Maven : mvn spring-boot:run.
Accédez à l'application via Swagger UI pour tester l'API à l'URL : http://localhost:8080/swagger-ui.html.
Tests Unitaires :

Des tests unitaires pour le contrôleur StudentController sont inclus dans le projet. Utilisez mvn test pour les exécuter.
Améliorations Possibles :
Gestion des erreurs : Implémenter une gestion des erreurs avec des codes et messages d'erreur personnalisés.
Validation des données : Ajouter des annotations de validation pour assurer la qualité des données.
Sécurité : Ajouter une couche de sécurité pour sécuriser les endpoints API.
Pagination : Ajouter la pagination pour les requêtes de données volumineuses.

## Vidéo:
https://github.com/user-attachments/assets/ff8604ad-ac12-4076-8121-fb348296ec01

## Auteur
Ce projet a été développé par Zaggar Driss.
