# Kit BED · Power365 Lille 2026

Trois fonctions DAX offertes aux participants de la session « Power BI : votre rapport a une carrosserie de F1, et un moteur de tondeuse ? », et une carte KPI à installer en quelques minutes.

## Télécharger

Le kit complet (fonctions, exemples, projet de démo) est dans l'onglet **Releases**, à droite de cette page : cliquez sur `Kit_BED_Power365.zip`.

## Les trois fonctions

| Fonction | Paramètres | Ce qu'elle fait |
|---|---|---|
| `BED.Controle` | `observe, attendu` | Affiche « ✔ OK » ou « ✘ Écart : +n » à côté d'un total sensible. |
| `BED.ListeFiltre` | `colonne, nbMax, libelleTout` | Un titre vivant : « Ferrari, Red Bull et 3 autres ». |
| `BED.KpiSvg` | `titre, valeur, reference, couleur, objectif` | Une carte KPI SVG avec icône qui réagit. Sans référence, un objectif (0.2 = +20 %) devient une barre avec drapeau. |

## Installer en 4 étapes

1. Ouvrez votre modèle dans Power BI Desktop, puis la vue TMDL.
2. Copiez le contenu de `BED_3_fonctions_script.tmdl` (à la racine de ce dépôt) et collez-le dans l'éditeur.
3. Cliquez sur **Appliquer**.
4. Créez une mesure qui appelle la fonction (exemples dans `BED_exemples_appel.dax`).

Le guide d'une page est dans `LISEZ-MOI.pdf`.

## Contenu du kit

- `LISEZ-MOI.pdf` : le guide d'installation.
- `BED_3_fonctions_script.tmdl`, `BED_KpiSvg_seule_script.tmdl` et `BED_exemples_appel.dax` : les scripts TMDL et les exemples d'appel DAX (dans le ZIP, ils sont rangés dans le dossier `1_Fonctions`).
- `2_Demo_Carte_KPI/` (dans le ZIP) : un projet Power BI autonome (données intégrées) pour voir la carte à côté d'une carte native. Ouvrez `Demo7_CarteKPI.pbip`, puis actualisez.

Patrick Jacquart · BEDFRANCE
