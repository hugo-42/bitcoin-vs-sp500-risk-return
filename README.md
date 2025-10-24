# Bitcoin : Risque vs Rendement

Projet d'analyse (capstone) évaluant le profil **risque/rendement** du Bitcoin sur une période récente.

**Livrables :** [Rapport HTML](report/bitcoin_report.html) · Slides (à venir dans `slides/`).

## Données
- Exemple fourni : `data/bitcoin_prices.csv` (mini-échantillon pour démonstration).
- Pour reproduire sur de vraies données, remplacez ce CSV par vos prix avec les colonnes :
  - `date` (YYYY-MM-DD)
  - `close` (prix de clôture / ajusté)

## Reproduire le rapport
Dans R (≥ 4.2) :
```r
install.packages(c("rmarkdown","knitr"), repos = "https://cloud.r-project.org")
rmarkdown::render("bitcoin_capstone.Rmd")
```

## Structure
- `bitcoin_capstone.Rmd` — code & analyse (base R, léger)
- `report/bitcoin_report.html` — rendu prêt à lire
- `data/` — CSV (placez ici vos données réelles)
- `slides/` — votre présentation (PDF/PPTX)
- `figs/` — images exportées (si vous en sauvegardez)
- `code/` — scripts annexes

## Licence
MIT — voir `LICENSE`.