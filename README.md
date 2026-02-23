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

## EXERCICE 9
lien: https://public.tableau.com/views/TP2-Visualisation-ChloM/Feuille1?:language=fr-FR&:sid=&:redirect=auth&publish=yes&showOnboarding=true&:display_count=n&:origin=viz_share_link


**3. Vérifiez dans l'écran "Source de données" :
Les types sont-ils corrects ? (# pour nombres, Abc pour texte)
Les nombres sont-ils bien reconnus ?**
- Has_death n'est pas un booléen pourtant en python c'est précisé que c'est un bool
**4. Créez un bar chart : Type_Catastrophe vs COUNT(ID_Catastrophe)
Les catégories sont-elles propres ? (pas de doublons)**
- oui !
**5. Créez un bar chart : Region vs SUM(Deces)
Les 5 régions sont-elles bien distinctes ?**
- oui !
**6. Créez une carte avec Country
Les pays sont-ils reconnus ?**
- non, Certains pays sont historiques ou regroupés pour la carte (ex : Yugoslavia → Serbie/Croatie, Soviet Union → Russie/Ukraine). 
Les petites îles ou territoires spéciaux (Hong Kong, Macao, Açores, Canaries) sont harmonisés pour la visualisation.

