# OM — Projection Budget 26/27

Simulateur de mercato et projection budgétaire pour la saison 2026/2027 de l'Olympique de Marseille.

## Contenu

- **`index.html`** — Simulateur interactif (single-file HTML, à ouvrir dans un navigateur ou déployé sur `mercato.gesputtij.me`). Permet de :
  - simuler les départs et leurs prix de cession (avec droits de revente)
  - ajouter des recrues (achat ferme, prêt sec, prêt + OA optionnelle/obligatoire)
  - voir en temps réel l'impact sur la masse salariale chargée, la balance mercato, le compte de résultat et la conformité DNCG/UEFA SCR
  - ajuster les hypothèses (cible MS, coefficient de charges, budget estimé)

- **`OM_26-27_Analyse_Revisee.txt`** — Note d'analyse révisée servant de base au scénario par défaut (effectif, arbitrages, recrutement, P&L cible).

## Usage

Ouvrir `index.html` dans un navigateur, ou utiliser la version déployée sur `mercato.gesputtij.me`. L'état est persisté localement via `localStorage`.

## Hypothèses par défaut

- Cible MS chargée : 95 M€
- Coefficient charges : 1,40
- Budget estimé : 200 M€
- Honoraires agents : 16 M€
- Autres charges : 105 M€
- Résultat financier : −5 M€
