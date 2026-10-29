# Walden Corp — Design System

Version documentaire : 1.0.0. Référence : dépôt ArnoldMenes1/waldencorp, branche main, commit c8b193c679adff1bb9b8a03dab0964a8d687d8d4. Site : https://waldencorp.vercel.app/

## Contenu
- brand.md : identité et principes visuels
- colors.md : palette et thèmes
- typography.md : polices et échelle typographique
- layout-spacing.md : grille, espacements et responsive
- assets-icons.md : logos, icônes et ressources
- components.md : composants et états
- motion.md : animations
- architecture.md : structure technique et routage
- pages/ : documentation de chaque page
- accessibility.md : accessibilité
- content.md : ton éditorial et SEO
- tokens.json / tokens.css : références de tokens
- governance.md : checklist de maintenance

## Source et limites
La documentation décrit la branche main au commit de référence. Les fichiers racine constatés comprennent index.html, 404.html, accessibilite.html, mentions-legales.html, politique-confidentialite.html, politique-cookies.html, robots.txt, sitemap.xml et vercel.json.

Le site utilise des pages HTML statiques avec CSS et JavaScript intégrés. Les tokens livrés ici sont documentaires : ils ne sont pas automatiquement consommés par les pages en production. Modifier tokens.css seul ne changera pas le site.

Les couleurs principales et la police de titre sont observées dans le code. Les échelles de spacing, rayons et animations sont des recommandations d'harmonisation, pas la preuve que chaque page les utilise déjà.

## Principes
1. Préserver les pages et parcours existants.
2. Préserver l'identité, les logos, le thème et le filigrane existants.
3. Préférer les modifications ciblées aux refontes involontaires.
4. Vérifier mobile, bureau, clair, sombre, clavier et réduction des mouvements.
5. Mettre à jour la documentation lorsque le code change.
