# Site web de [Naurellia](https://naurellia.com)

---

## À propos

Bienvenue sur Naurellia, votre portail vers la splendeur naturelle et l'authenticité insulaire de l'Île de Ré. Plongez dans une aventure immersive où la mer azur, les plages de sable doré et la vie insulaire prennent vie sous vos yeux.

Découvrez la Vie Insulaire : Notre blog exclusif est le reflet de la vie sur l'île. Rencontrez des habitants passionnés qui partagent leurs histoires, leurs expériences et leurs perspectives uniques. Des récits de pêcheurs aux escapades à vélo en passant par les moments de détente au bord de l'océan, notre blog vous transporte au cœur de la communauté insulaire.

Écologie et Bienfaits Durables : Explorez les contributions positives de nos gîtes, hôtels et commerces engagés dans des pratiques écologiques. Nous mettons en lumière leurs initiatives respectueuses de l'environnement et vous invitons à être inspirés par leur engagement en faveur de la durabilité.

Guide Touristique : Préparez-vous à vivre des expériences inoubliables grâce à notre guide touristique complet. Des coins secrets aux attractions incontournables, nous vous dévoilons les trésors cachés de l'île. Que vous soyez un voyageur passionné ou un explorateur curieux, notre guide est votre compagnon idéal pour découvrir chaque facette de l'Île de Ré.

Carte Interactive : Plongez dans une expérience interactive avec notre carte détaillée. Découvrez en un clin d'œil les meilleurs spots, les lieux recommandés et les adresses incontournables. Planifiez vos aventures en un instant et profitez au maximum de votre séjour.

Sous l'ombrage du bleu océan profond et la caresse du vert nature, Naurellia vous invite à vivre l'essence même de l'Île de Ré. Notre site est une invitation à la détente, à l'exploration et à la connexion avec la nature environnante. Joignez-vous à nous dans cette aventure insulaire où la beauté naturelle et la vie authentique s'entrelacent pour créer une expérience unique et mémorable.

Découvrez l'Île de Ré comme jamais auparavant, avec Naurellia.
N'hésitez pas à ajuster et personnaliser cette description selon vos préférences et la vision que vous avez pour votre site web.

---

## Installation

### Prérequis

- [php](https://www.php.net/downloads.php) >= 7.4
- [composer](https://getcomposer.org/download/)

### Installation

1. Clonez le dépôt git
2. Installez les dépendances avec `composer install`

---

## Commits

```text
06/08/2023 - Initialisation du projet
```

---

## Structure du projet

```text
.
├── bin (dossier des exécutables)
│   └── console
├── config (dossier de configuration)
│   ├── packages (dossier de configuration des packages)
│   ├── routes (dossier de configuration des routes)
│   ├── services.yaml
│   ├── routes.yaml
│   ├── preload.php
│   └── bundles.php
├── migrations (dossier des migrations)
├── public (dossier public)
│   ├── styles (dossier des styles)
│   ├── images (dossier des images)
│   └── index.php
├── src (dossier des sources)
│   ├── Controller (dossier des contrôleurs)
│   │   └── DefaultController.php
│   ├── Entity (dossier des entités)
│   ├── Repository (dossier des dépôts)
│   ├── Kernel.php
├── templates (dossier des templates)
│   ├── default (dossier des templates par défaut)
│   │   └── index.html.twig
│   └── base.html.twig
├── var (dossier des données)
│   ├── cache (dossier du cache)
│   └── log (dossier des logs)
├── vendor (dossier des dépendances)
├── .env (fichier de configuration de l'environnement)
├── .env.local (fichier de configuration de l'environnement local)
├── .gitignore (fichier d'ignorance git)
├── composer.json (fichier de configuration de composer)
├── composer.lock (fichier de verrouillage de composer)
├── docker-compose.yml (fichier de configuration de docker-compose)
├── docker-compose.override.yml (fichier de configuration de docker-compose en local)
├── readme.md (fichier de description du projet)
└── symfony.lock (fichier de verrouillage de symfony)
```

---

## Auteurs

- Anthony Mudet - Armotik

---

&copy; 2023 - Naurellia - Tous droits réservés - [Naurellia](https://naurellia.com)

Dernière mise à jour : 06/08/2023