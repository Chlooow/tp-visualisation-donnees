# TP3 — Visualisation de données massives

## Les Salons de Madame Lovelie

### Contexte

Madame Lovelie est prothésiste ongulaire et gère **5 salons de beauté** répartis à Rennes, Paris, Nice, Bordeaux et Cannes. Après une année complète d'activité (mars 2025 – mars 2026), elle souhaite analyser la performance de ses salons pour prendre des décisions stratégiques.

Elle vous confie un jeu de données de **5 500 rendez-vous** [`dataset_salons_lovelie.csv`](https://drive.google.com/file/d/1Bt84bNOfxEqzmkhe2pYE3uwCzaRIq49w/view?usp=sharing) contenant :

- l'identifiant de réservation
- les dates (réservation et prestation)
- l'heure
- le salon
- la catégorie et le nom de la prestation
- la durée
- le prix
- le canal de réservation (Planity, Site web, Téléphone, Sur place)
- le statut (Réalisé, Annulé, No-show, Reporté)
- les informations client
- le moyen de paiement
- la note de satisfaction
- un commentaire éventuel
- le nom de la praticienne.

Afin de l'accompagner dans ses prises de décisions, vous allez devoir construire des visualisations sur Tableau Public afin de répondre aux 9 questions ci-dessous.

---
### Lien Tableau
https://public.tableau.com/views/TP3-Visualisation-Chloe/Tableaudebord1?:language=fr-FR&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
---

### Questions

**Q1.** Quel est le chiffre d'affaires total généré par chaque salon ?

**Q2.** Quelle catégorie de prestation rapporte le plus de revenus dans chaque salon ?

**Q3.** Comment le chiffre d'affaires évolue-t-il mois par mois ? Y a-t-il une saisonnalité ?

**Q4.** Quel est le taux d'annulation et de no-show par salon ? Quel est le manque à gagner ?

**Q5.** Quel canal de réservation génère le plus de rendez-vous et lequel a le meilleur taux de réalisation ?

**Q6.** Quelles sont les 10 prestations les plus réalisées sur l'ensemble des salons ?

**Q7.** Quelle est la note de satisfaction moyenne par salon et par praticienne ?

**Q8.** Quels sont les créneaux horaires et jours de la semaine les plus demandés ?

> _Indice_ : pour extraire le jour de la semaine d'une date, créez un champ calculé avec `DATENAME('weekday', [date_prestation])`.

**Q9.** Quel est le panier moyen par salon et par catégorie ?

---

