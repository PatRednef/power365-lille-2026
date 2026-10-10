# Kit BED · Power365 Lille 2026

Quatre fonctions DAX offertes aux participants de la session « Power BI : votre rapport a une carrosserie de F1, et un moteur de tondeuse ? », et une carte KPI à installer en quelques minutes.

## Les quatre fonctions

| Fonction | Paramètres | Ce qu'elle fait |
|---|---|---|
| `BED.Controle` | `observe, attendu` | Affiche « ✔ OK » ou « ✘ Écart : +n » à côté d'un total sensible. |
| `BED.ListeFiltre` | `colonne, nbMax, libelleTout` | Un titre vivant : « Ferrari, Red Bull et 3 autres ». |
| `BED.BoutonSvg` | `libelle, couleur, plein, sens` | Un bouton de navigation SVG : pastille ronde avec flèche (suivant, retour ou lien externe), ombre colorée et reflet. |
| `BED.KpiSvg` | `titre, valeur, reference, couleur, objectif` | Une carte KPI SVG avec icône qui réagit. Sans référence, un objectif (0.2 = +20 %) devient une barre avec drapeau. |

## Installer en 4 étapes

1. Ouvrez votre modèle dans Power BI Desktop, puis la vue TMDL.
2. Ouvrez `BED_3_fonctions_script.tmdl` (ci-dessus), copiez tout le contenu et collez-le dans l'éditeur.
3. Cliquez sur **Appliquer**.
4. Créez une mesure qui appelle la fonction : des exemples sont dans `BED_exemples_appel.dax`. Pas de modèle sous la main ? Collez d'abord `BED_table_essai_script.tmdl`.

## À savoir en collant un script

Power BI Desktop peut vous demander de faire passer le niveau de compatibilité du modèle à une version supérieure : les fonctions DAX définies par l'utilisateur en ont besoin. C'est normal, vous pouvez accepter.

Ce changement ne se défait pas : le fichier peut ne plus s'ouvrir dans une ancienne version de Desktop. Faites donc une copie de votre fichier avant de coller le script, surtout s'il est partagé avec des collègues.

## Les fichiers de cette page

- `BED_3_fonctions_script.tmdl` : les trois fonctions, à coller dans la vue TMDL.
- `BED_KpiSvg_seule_script.tmdl` : la carte KPI seule.
- `BED_BoutonSvg_seule_script.tmdl` : le bouton de navigation seul.
- `BED_exemples_appel.dax` : des exemples d'appel.
- `BED_table_essai_script.tmdl` : une table Ventes d'essai (données intégrées) et ses mesures de base, pour tester dans un fichier vide. À coller avant les fonctions.
- `LISEZ-MOI.pdf` : le guide d'une page.

## Le kit complet, avec le projet de démo

Dans **Releases** (colonne de droite de cette page), téléchargez `Kit_BED_Power365.zip`, ou directement le fichier `Demo_Carte_KPI.pbix` pour ouvrir la démo d'un double-clic. Il contient tous les fichiers ci-dessus, rangés en dossiers, et un projet Power BI autonome pour voir la carte KPI à côté d'une carte native : ouvrez `Demo7_CarteKPI.pbip`, puis actualisez.

Patrick Jacquart · BEDFRANCE
