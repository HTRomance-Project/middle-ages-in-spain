HTRomance, Medieval Spain corpus of ground-truth for Handwritten Text Recognition
  and Layout Segmentation
=====================
![characters badge](badges/characters.svg) ![regions badge](badges/regions.svg) ![lines badge](badges/lines.svg) ![files badge](badges/files.svg)

<!-- Custom Zone -->

## Introduction

This ground-truth dataset has been carefully built around the idea of having generic data for building a strong and reliable model for HTR of Latin manuscripts. Each manuscript should have around 10 columns (5 bi-columns pages or 10 pages of single column).

Data follow the Segmonto guidelines.

> [!NOTE]
> The repository contains two XML files per image. The ones suffixed with `.chocomufin.xml` are normalized in order to be compliant with other datasets following the same guidelines. The others are more specific to this repository. We recommend using the normalized documents.


## Credits

- Transcriptions: Julie Bordier.
- Supervision and manuscript selection: Matthias Gille Levenson & Olivier Brisville-Fertin.
- Project management: Thibault Clérice & Alix Chagué.

<!-- Rien ne doit être modifié manuellement après la balise Start Auto -->

<!-- Start Auto -->

## Transcription guidelines

The transcription guidelines are described in a paper available on [HAL](https://hal-enc.archives-ouvertes.fr/hal-03828353) and published in the Journal for Open Humanities Data. The paper provides specific details about the selection process, the transcription methods and choices, as well as details about the output (mainly the [Generic CREMMA Model for Medieval Manuscripts (Latin and Old French)](https://zenodo.org/record/7234166#.Y7f69afMJhE) for [Kraken](https://kraken.re))

## Data

ALTO and images can be found in the directory called `data/`. Each subfolder of `data/` corresponds to a 
single manuscript, identified by its shelfmark.

<!-- BeginTable -->

| Shelfmark                                                            | Links                       | Range       | Type   |   Century | Color   |   Pages |   Main Zones |   Lines |   Characters | Genre                   | Content                                                                 |
|----------------------------------------------------------------------|-----------------------------|-------------|--------|-----------|---------|---------|--------------|---------|--------------|-------------------------|-------------------------------------------------------------------------|
| [BnF Espagnol 480](https://gallica.bnf.fr/ark:/12148/btv1b100347425) | [📁](data/bnf-espagnol-480) | 27r;39r;48r | prose  |        13 | ✗       |       3 |            3 |      80 |        11143 | juridique               | Documents relatifs à l'hôpital de Burgos                                |
| [BnF Espagnol 256](https://gallica.bnf.fr/ark:/12148/btv1b525184396) | [📁](data/bnf-espagnol-256) | 5r-8r       | prose  |        13 | ✓       |       7 |            7 |     225 |        12871 | juridique               | Fuero Juzgo                                                             |
| [BnF Espagnol 440](https://gallica.bnf.fr/ark:/12148/btv1b10033502d) | [📁](data/bnf-espagnol-440) | xr-yv       | prose  |        14 | ✗       |       4 |           16 |     353 |         8233 | juridique               | Siete Partidas                                                          |
| [BnF Espagnol 65](https://gallica.bnf.fr/ark:/12148/btv1b100361755)  | [📁](data/bnf-espagnol-65)  | 1r-6r       | prose  |        14 | ✗       |       6 |           22 |     738 |        16780 | juridique               | Fors de Navarre                                                         |
| [BnF Espagnol 44](https://gallica.bnf.fr/ark:/12148/btv1b52506309k)  | [📁](data/bnf-espagnol-44)  | 10r-12r     | prose  |        14 | ✓       |       5 |           10 |     416 |        12924 | hagiographie            | Légende dorée                                                           |
| [BnF Espagnol 563](https://gallica.bnf.fr/ark:/12148/btv1b100335333) | [📁](data/bnf-espagnol-563) | 51v-55r     | prose  |        14 | ✗       |       4 |            8 |     238 |        11786 | médecine                | Canon d'Avicenne                                                        |
| [BnF Espagnol 36](https://gallica.bnf.fr/ark:/12148/btv1b100295099)  | [📁](data/bnf-espagnol-36)  | 1r-3v       | prose  |        14 | ✓       |       6 |           12 |     469 |        14544 | roman chevaleresque     | Libro del caballero Zifar                                               |
| [BnF Espagnol 533](https://gallica.bnf.fr/ark:/12148/btv1b52501946f) | [📁](data/bnf-espagnol-533) | 1r-4v       | prose  |        15 | ✓       |       8 |            8 |     226 |         8511 | littérature épistolaire | Bursario                                                                |
| [BnF Espagnol 110](https://gallica.bnf.fr/ark:/12148/btv1b53158458z) | [📁](data/bnf-espagnol-110) | 1r-3r       | prose  |        15 | ✓       |       5 |            6 |     181 |        12897 | historiographie         | Suma de los reyes de España                                             |
| [BnF Espagnol 229](https://gallica.bnf.fr/ark:/12148/btv1b8436399x)  | [📁](data/bnf-espagnol-229) | 2r-6v       | mixed  |        15 | ✓       |      10 |           16 |     445 |        12096 | poésie + gloses         | Laberinto de Fortuna et gloses                                          |
| [BnF Espagnol 98](https://gallica.bnf.fr/ark:/12148/btv1b100327930)  | [📁](data/bnf-espagnol-98)  | 1r-4r       | prose  |        15 | ✗       |       4 |            9 |     244 |        11967 | protocole               | Ordinacions fetes per lo molt alt senyor en P[ere]                      |
| [BnF Espagnol 285](https://gallica.bnf.fr/ark:/12148/btv1b100345896) | [📁](data/bnf-espagnol-285) | 1r-6r       | prose  |        15 | ✗       |       6 |           12 |     296 |         7100 | généalogie              | El linaje donde bienen fijos e fijas de don fray Fernand Perez de Ayala |
| [BnF Espagnol 225](https://gallica.bnf.fr/ark:/12148/btv1b8452205t)  | [📁](data/bnf-espagnol-225) | 5r-8v       | vers   |        16 | ✓       |       8 |            9 |     198 |         5788 | poésie                  | Chansonnier catalan                                                     |
| [BnF Espagnol 548](https://gallica.bnf.fr/ark:/12148/btv1b100335316) | [📁](data/bnf-espagnol-548) | 1r-5r       | prose  |        16 | ✗       |       5 |            9 |     172 |         6624 | juridique               | Ordonnances des consuls de la mer                                       |
| [BnF Espagnol 368](https://gallica.bnf.fr/ark:/12148/btv1b100360337) | [📁](data/bnf-espagnol-368) | 2r-6r       | prose  |        16 | ✗       |       5 |            7 |     156 |         7586 | didactique              | Dialogos de los grados de perfecion..                                   |

<!-- EndTable -->

## Metrics

<!-- StartMetric -->

### Total number of pages

86

### Regions

- MainZone (154)
- NumberingZone (80)
- SealZone (2)
- MarginTextZone (60)
- StampZone (7)
- RunningTitleZone (14)
- QuireMarksZone (2)
- DropCapitalZone (76)

### Lines

- DefaultLine (4316)
- DropCapitalLine (118)
- HeadingLine (3)

<!-- EndMetric -->

## Funding

This project was funded by the Bibliothèque nationale de France through the 2022 project calls from
[Datalab](https://www.bnf.fr/fr/bnf-datalab) for 2023.

## Cite the project

> Clérice, T., Chagué, A., Gille-Levenson, M., Brisville-Fertin, O., Pinche, A., Camps, J., Fischer, F., Boschetti, F., Guadagnini, E., Guilhem Couffignal, G., Canteaut, O., Romary, L., Reboul, M., Perreaux, N., Poibeau, T., Smith, M., Norindr, J., Glaise, A., Navas Farré, M., Bordier, J., Leroy, N., Alba, R., & Rubin, G. *HTRomance* [Data set]. https://htromance-project.github.io/
```
@misc{Clerice_HTRomance,
author = {Clérice, Thibault and Chagué, Alix and Gille-Levenson, Matthias and Brisville-Fertin, Olivier and Pinche, Ariane and Camps, Jean-Baptiste and Fischer, Franz and Boschetti, Federico and Guadagnini, Elisa  and Guilhem Couffignal, Gilles and Canteaut, Olivier and Romary, Laurent and Reboul, Marianne and Perreaux, Nicolas and Poibeau, Thierry and Smith, Marc and Norindr, Jade and Glaise, Anthony and Navas Farré, Marina and Bordier, Julie and Leroy, Noé and Alba, Rachele and Rubin, Giorgia},
title = {{HTRomance}},
url = {https://htromance-project.github.io/}
}
```

## Infrastructure

This project relied on the [CREMMA infrastructure](https://www.dim-map.fr/projets-soutenus/cremma/).

