HTRomance: Corpus ???
=====================
![characters badge](badges/characters.svg) ![regions badge](badges/regions.svg) ![lines badge](badges/lines.svg) ![files badge](badges/files.svg)

<!-- Custom Zone -->

## Introduction

This ground-truth dataset has been carefully built around the idea of having generic data for building a strong and reliable model for HTR of Latin manuscripts. Each manuscript should have around 10 columns (5 bi-columns pages or 10 pages of single column).

Data follow the Segmonto guidelines.

## Credits

- Transcriptions: Julie Bordier.
- Supervision and manuscript selection: Matthias Gille Levenson & Olivier Brisville-Fertin.
- Project management: Thibault Clérice & Alix Chagué.

<!-- Rien ne doit être modifié manuellement après la balise Start Auto -->

<!-- Start Auto -->

## Transcription guidelines

The transcription guidelines are described in a paper available on [HAL](https://hal-enc.archives-ouvertes.fr/hal-03828353) and published at the Journal for Open Humanities Data. It provides specific details about the selection process, the transcription methods and choices, as well as details about output (mainly the [Generic CREMMA Model for Medieval Manuscripts (Latin and Old French)](https://zenodo.org/record/7234166#.Y7f69afMJhE) for [Kraken](https://kraken.re))

## Data

ALTO and images can be found in the directory data. Each subfolder of data corresponds to a 
single manuscript, identified by its bookshelf.

<!-- BeginTable -->

| Shelfmark                                                            | Folder                                           | Biblissima   | Range   | Type   |   Century | Color   |   Main Zones |   Lines |   Characters | Genre      | Content                                                                 |
|----------------------------------------------------------------------|--------------------------------------------------|--------------|---------|--------|-----------|---------|--------------|---------|--------------|------------|-------------------------------------------------------------------------|
| [BnF Espagnol 256](https://gallica.bnf.fr/ark:/12148/btv1b525184396) | [🔗](middle-ages-in-spain/data/bnf-espagnol-256) |              | xr-yv   | prose  |        13 | ✓       |            7 |     219 |        12830 | juridique  | Fuero Juzgo                                                             |
| [BnF Espagnol 65](https://gallica.bnf.fr/ark:/12148/btv1b100361755)  | [🔗](middle-ages-in-spain/data/bnf-espagnol-65)  |              | xr-yv   | prose  |        14 | ✗       |           22 |     734 |        16583 | juridique  | Fors de Navarre                                                         |
| [BnF Espagnol 285](https://gallica.bnf.fr/ark:/12148/btv1b100345896) | [🔗](middle-ages-in-spain/data/bnf-espagnol-285) |              | 1r-6r   | prose  |        15 | ✗       |           12 |     296 |         7100 | généalogie | El linaje donde bienen fijos e fijas de don fray Fernand Perez de Ayala |
| [BnF Espagnol 368](https://gallica.bnf.fr/ark:/12148/btv1b100360337) | [🔗](middle-ages-in-spain/data/bnf-espagnol-368) |              | 2r-6r   | prose  |        16 | ✗       |            7 |     156 |         7586 | didactique | Dialogos de los grados de perfecion..                                   |
| [BnF Espagnol 225](https://gallica.bnf.fr/ark:/12148/btv1b8452205t)  | [🔗](middle-ages-in-spain/data/bnf-espagnol-225) |              | 5r-8v   | vers   |        16 | ✓       |            9 |     195 |         5785 | poésie     | Chansonnier catalan                                                     |

<!-- EndTable -->

## Metrics

<!-- StartMetric -->

### Regions

- MainZone (57)
- DropCapitalZone (45)
- text (1)
- NumberingZone (33)
- MarginTextZone (34)
- Not specified (5)
- DecorationZone (9)
- StampZone (2)

### Lines

- DefaultLine (1215)
- default (295)
- Not specified (90)

<!-- EndMetric -->

## Funding

This project was funded by the Bibliothèque nationale de France through the 2022 project calls from
[Datalab](https://www.bnf.fr/fr/bnf-datalab).

## Citer le projet

ToDo.

## Infrastructure

This project was produced through the [CREMMA infrastructure](https://www.dim-map.fr/projets-soutenus/cremma/).

