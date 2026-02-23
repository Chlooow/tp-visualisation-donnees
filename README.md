# TP 2 — Préparation des données avec Python

## Objectif

Nettoyer le dataset `catnat_dirty.csv` et produire un fichier propre `catnat_clean.csv` prêt à être analysé dans Tableau.

Télécharger `catnat_dirty.csv`

## Problèmes à résoudre

Le dataset contient volontairement :

- ~150 doublons
- Valeurs manquantes supplémentaires
- Incohérences de casse (Asia, ASIA, asia...)
- Espaces parasites
- Variantes d'orthographe (USA, US, United States...)
- `Start Year` en format texte avec erreurs ("2020 AD", "Year 2020")
- Outliers aberrants (décès négatifs, magnitude à 999)

EXERCICE 9 :
lien: https://public.tableau.com/views/TP2-Visualisation-ChloM/Feuille1?:language=fr-FR&:sid=&:redirect=auth&publish=yes&showOnboarding=true&:display_count=n&:origin=viz_share_link
