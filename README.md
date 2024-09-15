# Dépôt pour la reconnaissance automatique d'écriture manuscrite sur les sources du DAGER et du SHL

Ce dépôt contient tous les fichiers qui ont été mobilisés pour le projet-test d'HTR dans le cadre de notre mémoire. Ci-dessous, vous trouverez la description des principaux fichiers inclus dans ce dépôt.

## Fichiers CSV

- `corpus_dager.csv` : Fichier d'importation pour les métadonnées du corpus DAGER. Chaque ligne correspond à un document avec ses métadonnées (titre, description, auteur, date, etc.).
- `corpus_shl.csv` : Fichier d'importation pour le corpus SHL avec des métadonnées similaires à celles du corpus DAGER.

## Modèle HTR

- `modele_htr_lectaurep/` : Dossier contenant le modèle HTR Lectaurep pour la reconnaissance des textes manuscrits. Il comprend les fichiers suivants :
  - `lectaurep_model.h5` : Modèle pré-entraîné pour la transcription automatique.
  - `lectaurep_config.json` : Fichier de configuration pour l'intégration du modèle dans les pipelines HTR.

## Utilisation

1. **Fichiers CSV** : Importez les fichiers CSV dans la plateforme Nakala pour ajouter les documents avec leurs métadonnées.
2. **Modèle Lectaurep** : Utilisez le modèle HTR pour la transcription automatique de textes manuscrits en suivant les instructions dans le dossier du modèle.
