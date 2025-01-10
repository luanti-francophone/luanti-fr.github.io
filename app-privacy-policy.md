---
title: Politique de Confidentialité de Luanti
description: Politique de confidentialité pour l'application Luanti.
small: |
  Dernière mise à jour : 17 août 2024
  (<a href="https://github.com/minetest/minetest.github.io/commits/master/app-privacy-policy.md">Voir les modifications</a>)
layout: page_subtitle
---

<style>
	h2 {
		margin-top: 5rem !important;
	}
</style>

Luanti peut se connecter aux services suivants pendant son fonctionnement :

* Le site principal (www.minetest.net) : utilisé pour obtenir la version la plus récente.
* La liste des serveurs : utilisée pour charger la liste des serveurs dans "Jouer en ligne".
* ContentDB : utilisé pour installer/mettre à jour du contenu dans le menu principal.
* Serveurs de jeu : serveurs tiers lors de parties en ligne.

Note : cette politique s'applique uniquement à l'application Luanti. L'accès aux services mentionnés via un navigateur web n'est pas couvert.

### Table des matières

- [Chargement de la liste des serveurs](#chargement-de-la-liste-des-serveurs)
  - [Informations collectées](#informations-collectees)
  - [Utilisation](#utilisation)
  - [Accès aux données](#acces-aux-donnees)
  - [Période de rétention](#periode-de-retention)
  - [Localisation](#localisation)
- [ContentDB](#contentdb)
  - [Informations collectées](#informations-collectees-1)
  - [Utilisation](#utilisation-1)
  - [Accès aux données](#acces-aux-donnees-1)
  - [Période de rétention](#periode-de-retention-1)
  - [Localisation](#localisation-1)
  - [Demandes de suppression](#demandes-de-suppression)
- [Vérification des versions](#verification-des-versions)
  - [Informations collectées](#informations-collectees-2)
  - [Utilisation](#utilisation-2)
- [Jeu en ligne](#jeu-en-ligne)
- [Tiers](#tiers)
- [Modifications futures de la politique de confidentialité](#modifications-futures-de-la-politique-de-confidentialite)


## Chargement de la liste des serveurs

### Informations collectées

Lorsque vous ouvrez l'onglet Jouer en ligne, Luanti demandera la liste des serveurs. Les informations suivantes seront transmises ou incluses :

* Adresse IP
* Version de Luanti
* Plateforme et système d'exploitation

### Utilisation

Les requêtes HTTP sont enregistrées pour aider au débogage, au développement et au support utilisateur. Elles peuvent également être utilisées pour générer des statistiques anonymisées et agrégées.

### Accès aux données

sfan5 gère la liste des serveurs et a accès aux journaux. Les journaux peuvent être partagés avec d'autres pour aider au débogage, au support utilisateur ou à la lutte contre les abus.

### Période de rétention

Les requêtes HTTP enregistrées sont conservées pendant une période maximale de 3 mois.

### Localisation

La liste des serveurs est actuellement hébergée aux Pays-Bas.

## ContentDB

Vous pouvez trouver plus d'informations sur
[la politique de confidentialité de ContentDB](https://content.minetest.net/privacy_policy/).

### Informations collectées

Des requêtes vers [ContentDB](https://content.minetest.net) seront effectuées dans le menu principal lors de l'utilisation de la fonctionnalité ContentDB. Cela inclut la vérification des mises à jour si vous avez installé des packages de ContentDB. Les informations suivantes seront transmises ou incluses :

* Adresse IP
* URL de la page
* Version de Luanti
* Plateforme et système d'exploitation

Par exemple :

```
11.22.33.44 content.minetest.net - [06/July/2024:10:05:00 +0200] "GET /packages/Wuzzy/glitch/releases/18414/download/?reason=new HTTP/2.0" 302 233 "-" "Luanti/5.8.0 (Windows/10.0.19041 x86_64)"
```


### Utilisation

Les requêtes HTTP sont enregistrées pour aider au débogage, au développement et aux statistiques agrégées.

Les requêtes (comme les téléchargements) sont utilisées pour des statistiques agrégées et pour calculer la popularité des packages. Les comptes de téléchargement sont affichés pour chaque package et chaque version, et des graphiques de téléchargement sont également disponibles.

L'information concernant si une adresse IP a téléchargé un package ou une version est mise en cache pour éviter de compter plusieurs fois les téléchargements par adresse IP, mais cette information est régulièrement supprimée.

### Accès aux données

rubenwardy gère ContentDB et a accès aux journaux. Les journaux peuvent être partagés avec d'autres pour aider au débogage, au support utilisateur ou à la lutte contre les abus.

### Période de rétention

Les requêtes HTTP enregistrées sont automatiquement supprimées après 14 jours.  
L'information sur les téléchargements par adresse IP est également supprimée après 14 jours.

### Localisation

ContentDB est actuellement situé en Allemagne, et les sauvegardes sont stockées au Royaume-Uni et/ou dans l'UE. En utilisant ce service, vous acceptez que les données soient transférées au sein du Royaume-Uni et/ou de l'UE.

### Demandes de suppression

Voir [la politique de confidentialité de ContentDB](https://content.minetest.net/privacy_policy/#removal-requests).

## Vérification des versions

### Informations collectées

Lorsque vous ouvrez Luanti, il peut contacter www.minetest.net pour récupérer des informations sur la version la plus récente. Les informations suivantes seront transmises ou incluses :

* Adresse IP
* Version de Luanti
* Plateforme et système d'exploitation

### Utilisation

Les informations de version sont hébergées sur GitHub Pages.  
Voir [À propos de GitHub Pages > Collecte des données](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages#data-collection) :

> Lorsqu'un site GitHub Pages est visité, l'adresse IP du visiteur est enregistrée et stockée à des fins de sécurité, que le visiteur soit connecté ou non à GitHub. Pour plus d'informations sur les pratiques de sécurité de GitHub, voir
> [Déclaration de confidentialité de GitHub](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement).

## Jeu en ligne

Luanti vous permet de jouer en ligne sur des serveurs multijoueurs. Notez que ces serveurs sont gérés par des tiers. Luanti agit comme un navigateur web se connectant à un site. Veuillez consulter la politique de confidentialité du serveur de jeu.

## Tiers

Nous ne partageons aucune information personnelle avec des tiers.

## Modifications futures de la politique de confidentialité

Nous informerons des futures modifications de cette politique de confidentialité via des publications sur le forum Luanti et par la date de dernière mise à jour en haut de cette page.
