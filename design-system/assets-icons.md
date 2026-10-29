# Logos, icônes et ressources

## Fichiers existants dans main

| Fichier | Usage attendu |
|---|---|
| logo only bleu beige.png | Logo principal |
| Icon_Only_Blue-removebg.png | Variante icône seule |
| favicon-blue.ico | Favicon |
| sitemap.xml | Sitemap |
| robots.txt | Directives aux robots |

Les fichiers sont présents à la racine au commit de référence. Confirmer visuellement le rôle d'une variante avant remplacement.

## Règles logo
- Respecter les proportions originales.
- Ne pas étirer, recolorer ou recadrer arbitrairement.
- Maintenir une marge libre autour du symbole.
- Choisir une variante adaptée au fond.
- Utiliser un alt pertinent si le logo transmet l'identité ; alt vide si l'image est redondante avec un nom adjacent.

## Icônes
Le site est principalement en HTML, CSS et JavaScript. Des pictogrammes SVG peuvent être intégrés dans les pages ; aucune bibliothèque globale d'icônes n'est établie comme dépendance confirmée dans la branche auditée.

Convention recommandée :
- SVG pour les pictogrammes simples.
- Trait homogène de 1.7–2 px.
- 18–24 px pour les contrôles ; 32–48 px pour les pictogrammes de cartes.
- Masquer les icônes décoratives aux technologies d'assistance.
- Donner un nom accessible aux boutons à icône seule.
- Ne pas remplacer une icône fonctionnelle par un emoji.

## Ressources externes
Google Fonts est une dépendance réseau. Le site doit rester lisible si elle échoue. Évaluer performance, confidentialité et maintenance avant d'ajouter un CDN ou une bibliothèque.

## Ajouter un asset
Nom descriptif, poids optimisé, rendu vérifié en clair/sombre, documentation mise à jour et texte alternatif vérifié.
