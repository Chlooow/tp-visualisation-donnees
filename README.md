# TP Noté — Visualisation de données avec Tableau Public

## Élections Municipales 2026 en France

---

> **AVERTISSEMENT** : Ce jeu de données est **entièrement synthétique** et fictif. Il a été généré à des fins pédagogiques uniquement. Les résultats, candidats et scores **ne correspondent à aucune réalité électorale**. Toute ressemblance avec des résultats réels serait purement fortuite.

---

### Contexte

À l'issue des élections municipales de 2026, un cabinet de conseil en communication politique souhaite analyser les résultats sur un échantillon de **108 communes de France métropolitaine** couvrant les 13 régions. Le cabinet dispose d'un jeu de données de **735 lignes** contenant les résultats des deux tours pour 10 formations politiques (RN, LR, RE, MoDem, HOR, PS, EELV, LFI, PCF, REC).

**Télécharger le dataset** : [`elections_municipales_2026.csv`](https://drive.google.com/file/d/1H3ywDaOhxiZqwsYB0g1E_qssn4Jcvbq5/view?usp=sharing)

Chaque ligne représente le résultat d'un candidat dans une commune à un tour donné. Le fichier contient : les identifiants de la commune (nom, code INSEE, département, région), la population, les données de participation (inscrits, votants, abstentions, blancs, nuls, exprimés), le tour (1 ou 2), les informations du candidat (nom, parti, sigle, position politique, nuance), ses voix, ses pourcentages, s'il a été élu, ainsi que les coordonnées GPS (latitude, longitude) de la commune.

Votre mission consiste à réaliser les visualisations demandées sur Tableau Public pour éclairer l'analyse politique du cabinet.

---

### Consignes

- Importez le CSV dans Tableau Public et vérifiez les types de données.
- Créez **une feuille par question** avec la visualisation appropriée.
- Le type de graphique attendu est indiqué entre parenthèses à la fin de chaque question.

Chaque ligne du dataset représente un **candidat** (pas une commune). Certaines informations comme la participation, les abstentions, les bulletins blancs et nuls sont donc répétées sur plusieurs lignes pour une même commune.

---

### Questions

**Q1.** Quelle est la répartition des communes remportées par chaque parti ? (Treemap ou bar chart horizontal)

**Q2.** En vous plaçant au **1er tour**, quel est le taux de participation moyen par région ? (Bar chart horizontal)

**Q3.** Comment se répartissent les voix entre les différentes positions politiques (extrême droite, droite, centre, gauche, gauche radicale) au 1er tour, à l'échelle nationale ? (Barres empilées 100% ou treemap)

**Q4.** Quel est le score moyen (% des exprimés) de chaque parti au 1er tour ? Quels partis dépassent les 15% en moyenne ? (Bar chart vertical)

**Q5.** En vous basant sur le **1er tour**, quelles sont les 10 communes où le taux d'abstention est le plus élevé ? (Carte de symboles ou bar chart horizontal)

**Q6.** Quel est le score moyen de chaque parti par région au 1er tour ? (Heatmap)

**Q7.** Au **1er tour**, quelle est la répartition des bulletins blancs par rapport aux votants, par région ? (Heatmap)

**Q8.** Au **2nd tour**, quelle est la répartition des bulletins nuls par rapport aux votants, par région ? (Heatmap)

**Q9.** Construisez une carte de France selon le parti vainqueur dans chaque commune. (Carte de symboles)

---

> **Livrable** : Lien Tableau Public + synthèse écrite de votre analyse des grandes tendances politiques observées (2 page max).
