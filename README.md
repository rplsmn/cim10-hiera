# cim10-hiera

Hiérarchies (groupes) de la **CIM-10 FR à usage PMSI 2026** — Volume 1, Table analytique.

## Fichier

- `cim10_hierarchies.csv` — 268 groupes, schéma `hiera;lib;code_deb` (séparateur `;`, UTF-8) :
  - `hiera` : `chapitre.groupe` (zero-paddé), ex. `01.01`, `01.02`, `22.02`
  - `lib` : libellé du groupe tel que dans la « Liste des catégories à trois caractères »
  - `code_deb` : code CIM-10 de début de la plage du groupe, ex. `A00`, `A15`, `U82`

## Source

ATIH, [CIM-10 FR à usage PMSI 2026](https://www.atih.sante.fr/cim-10-fr-usage-pmsi-2026) — annexe I du Bulletin officiel Santé n° 2026/14 du 04/06/2026 (arrêté AFSH1638462A), section « Liste des catégories à trois caractères » (pages imprimées 32–89).
