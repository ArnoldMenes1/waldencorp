# Mise en page et espacement

## Grille observée
Le site utilise CSS Grid et Flexbox. La largeur maximale de contenu observée sur l'accueil est d'environ 1240 px, avec des marges latérales fluides.

## Règles recommandées
- Largeur maximale bureau : 1200–1240 px.
- Marges latérales autour de 5vw, avec un minimum de 16–20 px sur mobile.
- Largeur de lecture : 60–75 caractères par ligne.
- Utiliser minmax(0, 1fr) dans les grilles pour limiter les débordements.
- Empiler les colonnes lorsque leur contenu devient trop étroit.
- Éviter les largeurs fixes qui dépassent la fenêtre.

## Échelle d'espacement proposée

| Token | Valeur | Usage |
|---|---:|---|
| space-1 | 4 px | Micro-écarts |
| space-2 | 8 px | Écart compact |
| space-3 | 12 px | Groupes serrés |
| space-4 | 16 px | Standard |
| space-5 | 20 px | Espacement de groupe |
| space-6 | 24 px | Cartes compactes |
| space-8 | 32 px | Sections internes |
| space-10 | 40 px | Rupture de groupe |
| space-12 | 48 px | Sections larges |
| space-16 | 64 px | Grandes séparations |
| space-20 | 80 px | Sections majeures |

Échelle de cohérence proposée, pas la preuve que toutes ces valeurs sont déjà utilisées.

## Rayons et profondeur
- Cartes : conserver le motif géométrique de la page existante.
- Champs : rayon confortable et cohérent.
- Bordures : 1 px généralement, 1.5–2 px pour un accent.
- Ombres légères, utilisées uniquement pour séparer les surfaces.
- Limiter les familles de rayons dans une composition.

## Responsive
| Largeur | Comportement |
|---|---|
| ≤ 440 px | Une colonne, padding compact, CTA large |
| 441–720 px | Une colonne ou deux colonnes si lisible |
| 721–1000 px | Grilles adaptatives |
| > 1000 px | Multi-colonnes et contenu plafonné |

Tester à 320, 375, 768, 1024 et 1440 px. Les contrôles tactiles devraient viser au moins 44 × 44 px. Vérifier safe areas, paysage et absence de recouvrement par les menus fixes.
