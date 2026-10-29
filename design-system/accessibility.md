# Accessibilité et qualité d'interface

## Cible
Prendre WCAG 2.2 niveau AA comme référentiel de conception, sans déclarer une conformité globale avant un audit complet.

## Structure et sémantique
- Un H1 descriptif et une hiérarchie logique.
- Éléments HTML adaptés à leur rôle.
- Labels explicites pour les champs.
- Liens dont le libellé décrit l'action.
- Langue du document correctement déclarée.

## Clavier
Toutes les actions sont utilisables sans souris, l'ordre de tabulation est cohérent, le focus est visible et non masqué, et aucun piège clavier n'existe.

## Contraste et lisibilité
Cible minimale : 4.5:1 pour le texte courant et 3:1 pour le texte large. Les contrôles et le focus doivent rester visibles. Le zoom doit être pris en charge et aucune hauteur fixe ne doit couper le contenu.

## Mouvement, images et formulaires
Respecter prefers-reduced-motion. Garder le contenu visible si une animation échoue. Fournir une alternative aux images informatives, alt vide aux images décoratives et un nom accessible aux boutons à icône seule. Les erreurs de formulaire doivent être exprimées en texte.

## Procédure
Tester clavier, zoom à 200 %, petit écran, contrastes et lecteur d'écran lorsque possible. Documenter les problèmes connus.
