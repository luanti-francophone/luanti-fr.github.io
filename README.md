# [Site Web francophone de Luanti](https://www.luanti.fr)

[![Statut de la build](https://github.com/minetest/minetest.github.io/workflows/build/badge.svg)](https://github.com/minetest/minetest.github.io/actions)\
Le site officiel de Luanti, accessible à l'adresse [www.luanti.fr](https://www.luanti.fr).

## Fonctionnalités

- Utilise le framework CSS [Bulma](https://bulma.io/).
- Adopte des techniques modernes de conception Web : unités `rem`, couleurs `hsl`.
- Site réactif et favicon inclus.

## Flux de développement

Ce site utilise le générateur de sites statiques [Jekyll](https://jekyllrb.com).

- Assurez-vous d'avoir installé [Ruby](https://www.ruby-lang.org/) version 2.4 ou supérieure.
- Installez [Bundler](https://bundler.io/) en exécutant `gem install bundler`.
  - Sur Linux, utilisez un gestionnaire de version Ruby tel que [rbenv](https://github.com/rbenv/rbenv)
    pour changer facilement de version et éviter les problèmes de permissions.
- Installez les dépendances en exécutant `bundle install`.
- Utilisez `bundle exec jekyll serve` pour construire automatiquement le site
  et le servir localement.

Vous pouvez également utiliser la configuration fournie pour un [conteneur de développement](https://containers.dev/) afin de simplifier le processus.

### Compatibilité des navigateurs

Lors de l'ajout de nouvelles fonctionnalités, gardez à l'esprit que ce site prend uniquement en charge les *navigateurs modernes* :

- Chrome (les deux versions les plus récentes)
- Edge (les deux versions les plus récentes)
- Firefox (les deux versions les plus récentes + la dernière version ESR)
- Opera (les deux versions les plus récentes)
- Safari (les deux versions les plus récentes)

Internet Explorer n'est pas pris en charge.

## Licence

Copyright © 2015-2020 Hugo Locurcio et ses contributeurs.

Sauf indication contraire, le code est sous licence MIT.  
Les médias (sauf la galerie) et le contenu sont sous licence  
[CC BY-SA 3.0 Unported](https://creativecommons.org/licenses/by-sa/3.0/).

Les captures d'écran de la galerie sont réalisées par différents auteurs et illustrent divers contenus :

1. Backrooms Test (Sumianvoice)  
2. Soothing32 (Zughy)  
3. i3 (Jean-Patrick Guerrero)  
4. Mineclone2 (Wuzzy)  
5. Steampunk Blimp (APercy)  
6. Animalia (ElCeejo)  
7. RPG16 texture pack (Hugues Ross)  
8. Minetest Game
