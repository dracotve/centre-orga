# Organisation System (Tamplate / Tamplate 2)

## Description
Ce projet est une interface type ordinateur / OS fictif permettant de gérer des organisations avec :
- Connexion utilisateur
- Système de permissions
- Gestion des membres
- Gestion des opérations
- Paramètres (couleur, ajout de membres, etc.)
- Notifications avec son
- Deux organisations séparées : Tamplate et Tamplate 2

---

## Fonctionnalités

### Interface
- Fond d’écran type PC
- Applications cliquables
- Fenêtre type système d’exploitation

### Connexion
- Login par organisation
- Nom + mot de passe
- Exemple :
  - admin / admin123

---

### Membres
Chaque membre possède :
- Nom
- Mot de passe
- Permissions :
  - Changer la couleur
  - Ajouter des membres
  - Ajouter des opérations

---

### Sécurité / Permissions
Les permissions contrôlent :
- Accès aux paramètres
- Ajout de membres
- Création d’opérations
- Modification du thème couleur

---

### Opérations
- Ajout d’opérations en temps réel
- Stockage en localStorage
- Affichage dynamique dans l’interface

---

### Notifications
- Notification en haut à droite
- Son intégré à chaque action :
  - Connexion
  - Ajout membre
  - Ajout opération
  - Changement de couleur

---

## Organisations disponibles

### Tamplate
- Couleur : rouge
- Admin par défaut :
  - user : admin
  - pass : admin123

### Tamplate 2
- Couleur : bleu
- Admin par défaut :
  - user : admin
  - pass : admin123

---

## Stockage
Toutes les données sont stockées en localStorage :
- Organisations
- Membres
- Opérations
- Permissions
- Couleurs

Aucune base de données serveur

---

## Installation
1. Télécharger le fichier HTML
2. Ouvrir dans un navigateur
3. Aucun serveur requis

---

## Important
- Projet 100% front-end
- Données locales uniquement
- Les données peuvent être supprimées si le cache du navigateur est vidé

---

## Améliorations possibles
- Base de données (Firebase / Node.js)
- Système de logs
- Sécurité avancée (hash mdp)
- Interface responsive mobile
- Système de rôles (Admin / Modérateur / Membre)

---

## Auteur
Projet custom généré pour système d’organisation RP / simulation OS
