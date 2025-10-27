# Netflix — Power BI Dashboard

Analyse du catalogue Netflix par **pays**, **types**, **genres** et **classements d’âge** (2008–2021) avec Power BI.

## Aperçus
<img src="Netflix-PowerBI-Dashboard/assets/Overview_1.png" width="49%"/> <img src="Netflix-PowerBI-Dashboard/assets/Overview_2.png" width="49%"/><br/>
<img src="Netflix-PowerBI-Dashboard/assets/Overview_3.png" width="49%"/> <img src="Netflix-PowerBI-Dashboard/assets/Overview_4.png" width="49%"/>

## Modèle de données
<img src="Netflix-PowerBI-Dashboard/assets/Modele_relations.png" width="80%"/>

## Points clés
- Table centrale **`Titles`** reliée à **ActorsDIM, CountryDIM, DirectorDIM, GenreDIM, RatingDIM**
- Mesures rangées dans **_Measures** : `01_KPI`, `02_Ratings`, `03_Genres`
- Mesure phare : **Share_Rating_in_Genre** (répartition des classifications d’âge au sein de chaque genre)

## Fichiers
- **Netflix_PowerBI.pbix** — ouvrir avec *Power BI Desktop*
- **assets/** — captures d’écran et schéma du modèle

---

*Power BI · DAX · Data Modeling*
