# Composants d'interface

Les pages sont actuellement statiques et peuvent avoir des variantes historiques. Une extraction en composants partagés est un chantier distinct.

## Header et navigation
Logo et nom identifiables ; navigation lisible ; état actif explicite si nécessaire ; contrôle de thème clavier-accessible ; sur mobile, éviter les liens trop proches ou les débordements non signalés. Un header superposé doit conserver le contraste.

## Bouton primaire
Fond safran #FFC233, texte sombre #0B1D42, libellé orienté action, hover discret, focus visible et hauteur cible d'au moins 44 px.

## Bouton secondaire
Fond transparent ou neutre, bordure lisible et importance visuelle inférieure au CTA primaire. Les états hover, focus et désactivé doivent être distincts.

## Cartes
Surface, bordure discrète et padding homogène. Titre court et contenu utile. Éviter les liens et boutons imbriqués dans une carte déjà cliquable.

## Liens
Distinguables du texte courant, focus visible et libellés descriptifs. Les destinations externes doivent être claires lorsqu'elles peuvent surprendre.

## Formulaires
- Label visible et programmatique pour chaque champ.
- Champs obligatoires indiqués avant soumission.
- Erreurs en texte, près du champ, pas uniquement par couleur.
- Conserver les données saisies après erreur lorsque possible.
- Messages de succès, erreur et chargement perceptibles.
- Vérifier réseau et navigation clavier.

## Footer
Liens regroupés par fonction, mentions légales et confidentialité faciles à trouver, colonnes empilées si nécessaire et contraste suffisant sur fond marine.

## Contrôle de thème
Nom accessible clair, préférence conservée entre pages et aucun changement de contenu inattendu. Ne pas dépendre uniquement de l'icône pour annoncer le thème.
