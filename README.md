# glyph-mosaic_likert-scale
Glyphs and Mosaic: Interactive Visualizations of Likert Scale Questionnaires

Projet de Data Visualization - Raphaël Diana et Alix Gonnot
Sujet : Visualisation de résultats de questionnaires comportant des échelles de Likert

Pour changer le data set de la visualisation Mosaïque le fichier doit respecter les pré-requis suivants :
- Le fichier doit être un csv
- Chaque line du fichier doit representer un individu, les colonnes contiennent ses réponses aux questions et autres renseignements sur lui.
- Chaque entête de colonne représentant une question doit commencer par "q\_"
- Chaque entête de colonne représentant une métadonnée doit commencer par "m\_"
- Le fichier ne doit pas contenir de valeurs manquantes
- Les valeurs des réponses dans les colonnes questions doivent seulement représenter des valeurs de réponses valides
  (il ne devrait pas y avoir de 0 pour représenter des valeurs manquantes)

  Pour changer le data set de la visualisation Glyphs le fichier doit respecter les pré-requis suivants :
  - Le fichier doit être un csv avec des <tab> à la place des virgules (tsv)
  - Le fichier ne doit pas contenir de valeurs manquantes
  - Les noms de questions doivent être de la forme "lettre+chiffre" (e.g. : A1, B13)
