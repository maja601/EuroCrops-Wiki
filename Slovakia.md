## Data Source
- Directly from [Národné poľnohospodárske a potravinárske centrum](http://www.nppc.sk/index.php/sk/) (recommended)
- [data.europa.eu](https://data.europa.eu/data/datasets/4c408849-80e9-41a2-8c93-08a65b7ce4fb?locale=sk) (As far as we know, the description of the culture is missing and the data is coarser in general)
## License Terms
> Licencia: Neposkytnutá žiadna licencia
([data.europa.eu](https://data.europa.eu/data/datasets/4c408849-80e9-41a2-8c93-08a65b7ce4fb?locale=sk))

_License: No License Provided_

## Attribute table and feature description for online accessible data
| Original attribute table column name |                                       |
| ------------------------------------ |---------------------------------------|
| ROK                                  | year                                  |
| ID_KD                                | ID KD                                 |
| ZKODKD                               |                                       |
| VYMERA                               | area extent                           |
| KODKD                                | code KD                               |
| **NUMKD**                            | value KD (40 classes)                 |
| **PORTS**                            | (99 classes)                          |
| LOKALITA                             | county                                |
| LOKALITA_C                           | county code                           |
| SPOSOBILOS                           | eligibility for subsidies             |
| SPOSOBIL_1                           | code of eligibility for subsidies     |
| ***KULTURA**                         | arable crop (9 classes)               |
| KULTURA_CI                           | code of arable crop                   |
| Shape_Leng                           |                                       |
| Shape_Area                           | area (in sq m)                        |

## Attribute table and feature description for requested data
| Original attribute table column name |                                       |
| ------------------------------------ |---------------------------------------|
| KODKD                                | code KD                               |
| PARCELA                              |                                       |
| PCUV                                 |                                       |
| VYMERA                               | area extent                           |
| Kultura                              |                                       |
| **Plodina**                          | crop name (174 classes)               |
| Shape_Leng                           |                                       |
| Shape_Area                           | area (in sq m)                        |

## Available years
2020, 2021, 2022

## Largest classes and stats
Data from 2021:

174 different classes

255,710 unique parcels with 532 being `NULL` 
