# OM — Projection Budget 26/27

Simulateur de mercato et projection budgétaire pour la saison 2026/2027 de l'Olympique de Marseille.

## Contenu

- **`index.html`** — Simulateur interactif V2 (single-file HTML, à ouvrir dans un navigateur ou déployé sur `mercato.gesputtij.me`). Permet de :
  - lire la synthèse du scénario en un coup d’œil : sport, finance, prochaine action
  - consulter l’effectif en lecture seule, organisé façon OM.FR
  - piloter les ventes et les recrues depuis l’onglet Mercato
  - tester les départs avec impact sur masse salariale, cash, plus-value et ratio effectif UEFA
  - ajouter des recrues avec discipline salariale : vente avant recrutement senior, cap recrue OM à 150 k€/mois brut, PRO 2 autorisés
  - projeter la compo et comprendre la trajectoire DNCG/financière dans un onglet pédagogique

- **`OM_26-27_Analyse_Revisee.txt`** — Note d'analyse révisée servant de base au scénario par défaut (effectif, arbitrages, recrutement, P&L cible).

## Usage

Ouvrir `index.html` dans un navigateur, ou utiliser la version déployée sur `mercato.gesputtij.me`. L'état est persisté localement via `localStorage`.

## Hypothèses par défaut

- Cible MS chargée : 94 M€
- Coefficient DNCG prudent : 1,90
- Budget estimé : 200 M€
- Honoraires agents : 16 M€
- Autres charges : 105 M€
- Résultat financier : −5 M€
