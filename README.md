## TP Spring Security 


## Objectif du TP

- Comprendre le fonctionnement de base de Spring Security en configurant :

- une authentification en mémoire,

- une gestion des rôles (USER / ADMIN),

- une protection des routes,

- une page de connexion personnalisée.

## Étape 1 – Création du projet

- Créer un projet Spring Boot via Spring Initializr avec :

- Spring Web

- Spring Security

- Thymeleaf

- Lancer l’application et accéder à http://localhost:8080.
Une page de connexion par défaut de Spring Security apparaît.

## Étape 2 – Sécurité par défaut

- Au premier lancement, Spring Security :

- protège toutes les routes,

- génère automatiquement un utilisateur nommé user,

- fournit un mot de passe aléatoire visible dans la console.

- Toutes les pages exigent une authentification.

## Étape 3 – Configuration personnalisée

- Créer une configuration Spring Security permettant de :

- définir deux utilisateurs en mémoire (admin et user),

- attribuer des rôles (ADMIN / USER),

- protéger certaines routes selon les rôles,

- autoriser la page de login.

## Étape 4 – Création des pages protégées

- Créer un contrôleur contenant :

- une page d’accueil accessible après connexion,

- un espace utilisateur accessible aux rôles USER et ADMIN,

- un espace administrateur accessible uniquement au rôle ADMIN.

- Tester :

**/user/dashboard → accessible par user + admin**

**/admin/dashboard → uniquement par admin**

## Étape 5 – Page de connexion personnalisée

- Créer une page HTML dans le dossier templates pour remplacer le formulaire de connexion par défaut.

- Configurer Spring Security pour utiliser :

- une page de login personnalisée,

- une redirection après succès,

- une redirection après déconnexion.


<img width="1918" height="576" alt="tp8 1" src="https://github.com/user-attachments/assets/414ebff4-ce69-4a53-823d-44db4079b9d8" />




<img width="648" height="537" alt="Capture d&#39;écran 2025-11-23 000538" src="https://github.com/user-attachments/assets/dfc6be3b-96d7-4fd4-a07f-11a9340bf4ef" />




<img width="719" height="333" alt="image" src="https://github.com/user-attachments/assets/4603181a-5537-4d6d-9468-51abb220f5dc" />

