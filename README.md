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

| Shelfmark                                                            | Folder                                                        | Biblissima   | Range   | Type   |   Century | Color   |   Main Zones |   Lines |   Characters | Genre               | Content                                                                 |
|----------------------------------------------------------------------|---------------------------------------------------------------|--------------|---------|--------|-----------|---------|--------------|---------|--------------|---------------------|-------------------------------------------------------------------------|
| [BnF Espagnol 256](https://gallica.bnf.fr/ark:/12148/btv1b525184396) | [🔗](../htromance/middle-ages-in-spain/data/bnf-espagnol-256) |              | 5r-8r   | prose  |        13 | ✓       |            7 |     219 |        12862 | juridique           | Fuero Juzgo                                                             |
| [BnF Espagnol 563](https://gallica.bnf.fr/ark:/12148/btv1b100335333) | [🔗](../htromance/middle-ages-in-spain/data/bnf-espagnol-563) |              | 51v-55r | prose  |        14 | ✗       |            8 |     238 |        11786 | médecine            | Canon d'Avicenne                                                        |
| [BnF Espagnol 65](https://gallica.bnf.fr/ark:/12148/btv1b100361755)  | [🔗](../htromance/middle-ages-in-spain/data/bnf-espagnol-65)  |              | 1r-6r   | prose  |        14 | ✗       |           22 |     734 |        16776 | juridique           | Fors de Navarre                                                         |
| [BnF Espagnol 36](https://gallica.bnf.fr/ark:/12148/btv1b100295099)  | [🔗](../htromance/middle-ages-in-spain/data/bnf-espagnol-36)  |              | 1r-3v   | prose  |        14 | ✓       |           12 |     469 |        14544 | roman chevaleresque | Libro del caballero Zifar                                               |
| [BnF Espagnol 110](https://gallica.bnf.fr/ark:/12148/btv1b53158458z) | [🔗](../htromance/middle-ages-in-spain/data/bnf-espagnol-110) |              | 1r-3r   | prose  |        15 | ✓       |            6 |     181 |        12897 | historiographie     | Suma de los reyes de España                                             |
| [BnF Espagnol 98](https://gallica.bnf.fr/ark:/12148/btv1b100327930)  | [🔗](../htromance/middle-ages-in-spain/data/bnf-espagnol-98)  |              | 1r-4r   | prose  |        15 | ✗       |            9 |     244 |        11967 | protocole           | Ordinacions fetes per lo molt alt senyor en P[ere]                      |
| [BnF Espagnol 285](https://gallica.bnf.fr/ark:/12148/btv1b100345896) | [🔗](../htromance/middle-ages-in-spain/data/bnf-espagnol-285) |              | 1r-6r   | prose  |        15 | ✗       |           12 |     296 |         7100 | généalogie          | El linaje donde bienen fijos e fijas de don fray Fernand Perez de Ayala |
| [BnF Espagnol 548](https://gallica.bnf.fr/ark:/12148/btv1b100335316) | [🔗](../htromance/middle-ages-in-spain/data/bnf-espagnol-548) |              | 1r-5r   | prose  |        16 | ✗       |            9 |     172 |         6624 | juridique           | Ordonnances des consuls de la mer                                       |
| [BnF Espagnol 368](https://gallica.bnf.fr/ark:/12148/btv1b100360337) | [🔗](../htromance/middle-ages-in-spain/data/bnf-espagnol-368) |              | 2r-6r   | prose  |        16 | ✗       |            7 |     156 |         7586 | didactique          | Dialogos de los grados de perfecion..                                   |
| [BnF Espagnol 225](https://gallica.bnf.fr/ark:/12148/btv1b8452205t)  | [🔗](../htromance/middle-ages-in-spain/data/bnf-espagnol-225) |              | 5r-8v   | vers   |        16 | ✓       |            9 |     195 |         5785 | poésie              | Chansonnier catalan                                                     |

<!-- EndTable -->

## Metrics

<!-- StartMetric -->

### Regions

- MainZone (101)
- NumberingZone (53)
- StampZone (4)
- MarginTextZone (42)
- DropCapitalZone (52)
- DecorationZone (9)
- text (1)
- Not specified (6)
- QuireMarksZone (1)

### Lines

- DefaultLine (2509)
- Not specified (97)
- default (298)

<!-- EndMetric -->

## Funding

This project was funded by the Bibliothèque nationale de France through the 2022 project calls from
[Datalab](https://www.bnf.fr/fr/bnf-datalab) for 2023.

## Citer le projet

> Clérice, T., Chagué, A., Gille-Levenson, M., Brisville-Fertin, O., Pinche, A., Camps, J., Fischer, F., Boschetti, F., Guadagnini, E., Guilhem Couffignal, G., Canteaut, O., Romary, L., Reboul, M., Perreaux, N., Poibeau, T., & Smith, M. *HTRomance* [Data set]. https://htromance-project.github.io/

```
@misc{Clerice_HTRomance,
author = {Clérice, Thibault and Chagué, Alix and Gille-Levenson, Matthias and Brisville-Fertin, Olivier and Pinche, Ariane and Camps, Jean-Baptiste and Fischer, Franz and Boschetti, Federico and Guadagnini, Elisa  and Guilhem Couffignal, Gilles and Canteaut, Olivier and Romary, Laurent and Reboul, Marianne and Perreaux, Nicolas and Poibeau, Thierry and Smith, Marc},
title = {{HTRomance}},
url = {https://htromance-project.github.io/}
}
```

## Infrastructure

This project relied on the [CREMMA infrastructure](https://www.dim-map.fr/projets-soutenus/cremma/).

