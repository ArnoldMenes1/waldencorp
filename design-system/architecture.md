# Architecture technique

## État observé dans main
Le site est statique : documents HTML, CSS et JavaScript intégrés. Les fichiers racine audités ne montrent pas de framework front-end ou de chaîne de compilation obligatoire.

## Fichiers racine
- index.html : accueil et point d'entrée principal.
- 404.html : page d'erreur statique.
- accessibilite.html : déclaration d'accessibilité.
- mentions-legales.html : mentions légales.
- politique-confidentialite.html : confidentialité.
- politique-cookies.html : cookies.
- robots.txt et sitemap.xml : indexation.
- vercel.json : réécriture des chemins.
- PNG et ICO : logo et favicon.

## Routage
Le vercel.json de référence réécrit /(.*) vers /index.html. Le routage public peut donc dépendre de la logique côté client ; 404.html existe aussi comme fichier statique. Ne pas supposer que chaque chemin propre correspond à un fichier HTML distinct.

Avant toute modification du routage : cartographier les liens, tester URL propres et anciennes URL à fragment, navigation directe, rechargement, retour navigateur, pages légales et réponse HTTP 404.

## État actuel versus évolution recommandée
Actuel : HTML statique, CSS/JS embarqués, couleurs récurrentes dans les pages, assets à la racine, déploiement Vercel.

Évolutions possibles mais non réalisées par ce guide :
- Extraire les variables dans une feuille CSS commune.
- Mutualiser header, footer, boutons, champs et cartes.
- Centraliser la gestion du thème.
- Ajouter des vérifications automatisées de liens, accessibilité et responsive.
- Migrer progressivement ; ne pas adopter un framework uniquement pour documenter les styles.

## Maintenance
Limiter chaque changement au périmètre demandé, tester les fonctions après modification, ne pas envoyer de données fictives en production et documenter tout changement d'architecture.
