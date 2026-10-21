# OM — Projection Budget 26/27

Simulateur de mercato et projection budgétaire pour la saison 2026/2027 de l'Olympique de Marseille.

## Contenu

- **`index.html`** — Simulateur interactif V2 (single-file HTML, à ouvrir dans un navigateur ou déployé sur `mercato.gesputtij.me`). Permet de :
  - construire directement une compo en 4-2-3-1 depuis la page par défaut
  - piloter les départs et les arrivées à droite du terrain
  - basculer entre un mode mercato réaliste avec alertes salariales/financières et un mode sans contrainte
  - placer des joueurs existants, des recrues ou des placeholders `RECRUE` sur le terrain
  - consulter l’effectif en lecture seule, organisé façon OM.FR
  - tester les départs avec impact sur masse salariale, cash, plus-value et ratio effectif UEFA

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
