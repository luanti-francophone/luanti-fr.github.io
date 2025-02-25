---
title: Politique de Confidentialité de Luanti
description: Politique de confidentialité pour l'application Luanti.
small: |
  Dernière mise à jour : 2024-08-17
  (<a href="https://github.com/luanti-org/luanti-org.github.io/commits/master/app-privacy-policy.md">Voir les mises à jour</a>)
layout: page_subtitle
---

<style>
	h2 {
		margin-top: 5rem !important;
	}
</style>

Luanti peut se connecter aux services suivants lors de son fonctionnement :

* Le site principal (www.luanti.org) : utilisé pour obtenir la version la plus récente
* La liste des serveurs : utilisée pour charger la liste des serveurs dans "Jouer en ligne"
* ContentDB : utilisé pour installer/mettre à jour du contenu dans le menu principal
* Serveurs de jeu : serveurs tiers lors du jeu en ligne

Remarque : cette politique s'applique uniquement à l'application Luanti. L'accès aux services mentionnés via un navigateur web n'est pas couvert.

### Table des matières

- [Chargement de la liste des serveurs](#chargement-de-la-liste-des-serveurs)
  - [Informations collectées](#informations-collectees)
  - [Utilisation des informations](#utilisation-des-informations)
  - [Qui a accès](#qui-a-acces)
  - [Période de rétention](#periode-de-retention)
  - [Emplacement](#emplacement)
- [ContentDB](#contentdb)
  - [Informations collectées](#informations-collectees-1)
  - [Utilisation des informations](#utilisation-des-informations-1)
  - [Qui a accès](#qui-a-acces-1)
  - [Période de rétention](#periode-de-retention-1)
  - [Emplacement](#emplacement-1)
  - [Demandes de suppression](#demandes-de-suppression)
- [Vérification de version](#verification-de-version)
  - [Informations collectées](#informations-collectees-2)
  - [Utilisation des informations](#utilisation-des-informations-2)
- [Jeu en ligne](#jeu-en-ligne)
- [Tiers](#tiers)
- [Modifications futures de la politique de confidentialité](#modifications-futures-de-la-politique-de-confidentialite)


## Chargement de la liste des serveurs

### Informations collectées

Lorsque vous ouvrez l'onglet "Jouer en ligne", Luanti demandera la liste des serveurs.
Les informations suivantes seront transférées ou incluses :

* Adresse IP
* Version de Luanti
* Plateforme et système d'exploitation

### Utilisation des informations

Les requêtes HTTP sont enregistrées pour faciliter le débogage, le développement et l'assistance utilisateur. Elles peuvent également être utilisées pour générer des statistiques anonymisées et agrégées.

### Qui a accès

sfan5 gère la liste des serveurs et a accès aux journaux. Ces journaux peuvent être partagés avec d'autres pour aider au débogage, à l'assistance utilisateur ou à la lutte contre les abus.

### Période de rétention

Les requêtes HTTP enregistrées sont conservées jusqu'à 3 mois.

### Emplacement

La liste des serveurs est actuellement hébergée aux Pays-Bas.


## ContentDB

Vous pouvez trouver plus d'informations sur la [politique de confidentialité de ContentDB](https://content.luanti.org/privacy_policy/).

### Informations collectées

Des requêtes à [ContentDB](https://content.luanti.org) seront effectuées dans le menu principal lors de l'utilisation de cette fonctionnalité. Cela inclut la vérification des mises à jour si vous avez installé des paquets depuis ContentDB. Les informations suivantes seront transférées ou incluses :

* Adresse IP
* URL de la page
* Version de Luanti
* Plateforme et système d'exploitation

Par exemple :

```
11.22.33.44 content.luanti.org - [06/Juillet/2024:10:05:00 +0200] "GET /packages/Wuzzy/glitch/releases/18414/download/?reason=new HTTP/2.0" 302 233 "-" "Luanti/5.8.0 (Windows/10.0.19041 x86_64)"
```

### Utilisation des informations

Les requêtes HTTP sont enregistrées pour faciliter le débogage, le développement et la génération de statistiques agrégées.

Les requêtes (comme les téléchargements) sont utilisées pour des statistiques agrégées et pour calculer la popularité des paquets. Les comptes de téléchargement sont affichés pour chaque paquet et chaque version, et des graphiques de téléchargement sont disponibles pour chaque paquet.

Le fait qu'une adresse IP ait téléchargé un paquet ou une version est mis en cache pour éviter que les téléchargements ne soient comptés plusieurs fois par adresse IP, mais cette information est supprimée régulièrement.

### Qui a accès

rubenwardy gère ContentDB et a accès aux journaux. Ces journaux peuvent être partagés avec d'autres pour aider au débogage, à l'assistance utilisateur ou à la lutte contre les abus.

### Période de rétention

Les requêtes HTTP enregistrées sont automatiquement supprimées après 14 jours.
Le fait qu'une adresse IP ait téléchargé un paquet ou une version est également supprimé après 14 jours.

### Emplacement

ContentDB est actuellement hébergé en Allemagne et les sauvegardes sont stockées au Royaume-Uni et/ou dans l'UE. En utilisant ce service, vous donnez votre accord pour que les données soient déplacées au sein du Royaume-Uni et/ou de l'UE.

### Demandes de suppression

Voir la [politique de confidentialité de ContentDB](https://content.luanti.org/privacy_policy/#removal-requests).


## Vérification de version

### Informations collectées

Lorsque vous ouvrez Luanti, celui-ci peut contacter www.luanti.org pour récupérer des informations sur la version la plus récente. Les informations suivantes seront transférées ou incluses :

* Adresse IP
* Version de Luanti
* Plateforme et système d'exploitation

### Utilisation des informations

Les informations de version sont hébergées sur GitHub Pages.
Voir [À propos de GitHub Pages > Collecte de données](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages#data-collection) :

> Lorsqu'un site GitHub Pages est visité, l'adresse IP du visiteur est enregistrée et stockée à des fins de sécurité, que le visiteur soit connecté à GitHub ou non. Pour plus d'informations sur les pratiques de sécurité de GitHub, consultez la [Déclaration de confidentialité de GitHub](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement).


## Jeu en ligne

Luanti vous permet de jouer en ligne sur des serveurs de jeu multijoueurs. Notez que ces serveurs sont des services tiers, Luanti agit comme un navigateur web se connectant à un site internet. Veuillez donc consulter la politique de confidentialité du serveur de jeu.


## Tiers

Nous ne partageons aucune information personnelle avec des tiers.


## Modifications futures de la politique de confidentialité

Toute modification future de la politique de confidentialité sera annoncée via des publications sur le forum de Luanti et indiquée par la date de dernière mise à jour en haut de cette page.
