# 📸 PhotoForYou

**Plateforme web de vente de photographies professionnelles**

PhotoForYou est un projet de développement web réalisé dans le cadre du **BTS SIO – Option SLAM (2ème année)**.

L'objectif est de développer une plateforme permettant aux photographes de proposer leurs créations et aux clients de découvrir et acheter des photographies en ligne.

Le projet est développé progressivement en PHP orienté objet, avec une base de données MySQL et une interface Bootstrap.

---

## 🎯 Objectifs du projet

- Développer une application web en PHP orienté objet (POO).
- Mettre en place une interface responsive avec Bootstrap.
- Gérer différents profils utilisateurs.
- Utiliser les sessions PHP pour gérer les utilisateurs connectés.
- Créer un menu de navigation dynamique selon le rôle.
- Préparer une architecture évolutive vers une authentification complète.
- Intégrer progressivement une base de données MySQL avec PDO.

## 👥 Gestion des utilisateurs

L'application prévoit quatre rôles :

| Rôle | Description |
|---|---|
| Visiteur | Consultation du catalogue et inscription. |
| Client | Consultation, panier et achats de photographies. |
| Photographe | Gestion de son profil et de ses photographies. |
| Administrateur | Administration de la plateforme et des utilisateurs. |

## 🛠️ Technologies utilisées

- **PHP** : programmation orientée objet.
- **HTML5** : structure des pages.
- **CSS3** : présentation.
- **Bootstrap 5** : interface responsive.
- **JavaScript** : interactions dynamiques.
- **PHP Sessions** : gestion des utilisateurs connectés.
- **MySQL / PDO** : gestion des données (évolutions du projet).

## 📂 Structure du projet

```text
PhotoForYou/
│
├── classes/
│   └── User.class.php
│
├── includes/
│   ├── header.php
│   └── footer.php
│
├── index.php
├── login.php
└── logout.php
```

## ⚙️ Installation

### Prérequis

- WAMP Server ou un environnement PHP équivalent.
- PHP.
- Un navigateur web.
- Git (facultatif).

### Installation locale

1. Cloner le repository :

```bash
git clone URL_DU_REPOSITORY
```

2. Placer le dossier `PhotoForYou` dans :

```text
C:\wamp64\www\
```

3. Démarrer les services Apache de WAMP.

4. Ouvrir le projet dans le navigateur :

```text
http://localhost/PhotoForYou/
```

5. Accéder à la page de connexion :

```text
http://localhost/PhotoForYou/login.php
```

## 🧪 Comptes de test

La première version utilise des comptes de test pour simuler les différents rôles.

| Identifiant | Rôle |
|---|---|
| visiteur | VISITEUR |
| client | CLIENT |
| photographe | PHOTOGRAPHE |
| admin | ADMIN |

Ces comptes servent uniquement à tester le fonctionnement du menu dynamique. Il ne s'agit pas encore d'un système d'authentification réel.

## 🔐 Sécurité

Les prochaines évolutions intégreront :

- Requêtes préparées avec PDO.
- Hachage des mots de passe.
- Validation des données côté client et serveur.
- Protection contre les injections SQL et les attaques XSS.
- Protection CSRF.
- Gestion sécurisée des sessions.
- Contrôle des autorisations selon les rôles.

## 🚀 Évolutions prévues

- [ ] Menu dynamique selon le rôle utilisateur.
- [ ] Inscription des clients et photographes.
- [ ] Authentification sécurisée.
- [ ] Gestion des profils utilisateurs.
- [ ] Gestion des photographies (CRUD).
- [ ] Catalogue et recherche multicritères.
- [ ] Panier et système de crédits.
- [ ] Gestion des commandes et achats.
- [ ] Interface d'administration.

## 🎓 Contexte pédagogique

Projet réalisé dans le cadre du BTS Services Informatiques aux Organisations (SIO), spécialité Solutions Logicielles et Applications Métiers (SLAM).

**Compétences travaillées :** PHP, POO, Bootstrap, sessions, gestion des rôles, SQL, PDO et sécurité web.

---

**PhotoForYou – Des pros au service des professionnels de la communication.**
