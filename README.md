# TP 8 : Authentification en mémoire avec Spring Security

## Objectif

Découvrir le fonctionnement fondamental de Spring Security en configurant une authentification en mémoire.

Ce TP permet de comprendre comment Spring intercepte les requêtes, vérifie les identifiants d'un utilisateur et accorde ou refuse l'accès selon son rôle.

## Compétences visées

- Comprendre le modèle d'authentification de Spring Security
- Créer des utilisateurs et rôles statiques
- Restreindre l'accès à certaines pages selon les rôles
- Personnaliser la page de connexion

## Structure du projet

 <img width="719" height="456" alt="Capture d’écran 2025-11-23 à 00 03 07" src="https://github.com/user-attachments/assets/4978e6be-7d72-418b-bdfe-1750915d7d21" />
 

## Utilisateurs configurés

- **Admin** : username=`admin`, password=`1234`, rôle=`ADMIN`
- **User** : username=`user`, password=`1111`, rôle=`USER`

## Routes et accès

- `/` - Accessible à tous les utilisateurs authentifiés
- `/login` - Accessible à tous (page de connexion)

- `/user/dashboard` - Accessible aux rôles USER et ADMIN
- `/admin/dashboard` - Accessible uniquement au rôle ADMIN


## Résultat : 

https://github.com/user-attachments/assets/d179b8a8-a9a0-4883-8177-db2662a1fd85

