# Couleurs et thèmes

## Palette claire observée

| Variable CSS | Valeur | Rôle |
|---|---|---|
| --bg | #EDF2FC | Fond principal bleu craie |
| --card | #FFFFFF | Surface |
| --ink | #0B1D42 | Texte principal |
| --mut | #4A5A7C | Texte secondaire |
| --navy | #0F2A55 | Bleu marine |
| --sky | #4C7DFF | Bleu électrique |
| --sun | #FFC233 | Safran |
| --line | #CBD6EE | Bordure claire |

## Palette sombre observée

| Rôle | Valeur |
|---|---|
| Fond | #06112A |
| Surface | #0C1E44 |
| Texte principal | #EAF0FF |
| Texte secondaire | #9DB0D8 |
| Bleu d'accent | #8FB0FF |
| Bordure | #1B3266 |
| Bordure secondaire | #2A4585 |
| Texte secondaire du footer | #B4C4E8 |
| Fond du footer sombre | #0A1A3C |

## Usage
Fond pour le canevas, surface pour cartes et champs, texte principal pour titres et informations essentielles, texte secondaire pour explications, bleu pour liens/états actifs, safran pour actions avec texte sombre, marine pour zones de marque et footer.

## Thème
Le code utilise des variables CSS et un attribut de thème à la racine. Le thème clair est le défaut observé. Ne pas écraser la préférence de l'utilisateur pendant la navigation.

- Vérifier les contrastes après chaque changement.
- Les états focus, hover, actif et désactivé ne doivent pas dépendre uniquement de la couleur.
- Garder un texte sombre lisible sur le safran.
- Ne pas ajouter de couleurs sans définir leur rôle.
