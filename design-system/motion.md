# Animations et interactions

## Intention
Les mouvements guident l'attention, indiquent un état ou donnent un retour. Ils ne doivent jamais être nécessaires à la compréhension.

## Durées recommandées
- Contrôles et hover : 150–220 ms.
- Entrée de section : 220–400 ms.
- Navigation : rapide, sans bloquer une action.
- Changement de thème : transition de couleur modérée.

Ces valeurs sont des repères et non un inventaire exhaustif des animations déjà codées.

## Principes
- Déplacements courts et courbes naturelles.
- Pas de flashs ni de secousses agressives.
- Ne pas retarder inutilement les liens.
- Respecter prefers-reduced-motion: reduce.
- Garder le contenu visible si JavaScript ou IntersectionObserver échoue.
- Préserver navigation arrière/avant.

## Contrôles
Tester au clavier, vérifier que le contenu essentiel n'est jamais masqué et que les animations décoratives se simplifient lorsque la réduction des mouvements est demandée.
