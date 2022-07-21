## Data Source
Download via WFS `https://www.ifap.pt/isip/ows/isip.data/wfs` or over the [IFAP website](https://www.ifap.pt/isip/ows/).
## License
From [Sistema Nacional de Informação Geográfica](https://snig.dgterritorio.gov.pt/rndg/srv/por/catalog.search#/metadata/5b514567-1590-45ce-82fa-e9bb84a95b34):

```
Política de Dados
Classificação            Não classificado
Restrições legais        Acesso público limitado de acordo com o Artigo 13(1)(e) da Diretiva INSPIRE
                         Serviço de visualização sem restrições. Serviço de descarregamento sujeirto a direitos de propriedade intelectual
Restrições de recurso    Sem restrições
```

```
Data Policy
Classification           Not classified
Legal Restriction        Public access limited in accordance with Article 13(1)(e) of the INSPIRE Directive
                         Unrestricted viewing service. Downloading service subject to intellectual property rights
Feature Restrictions     Unrestricted
```

## Attribute table and feature description 
| Original attribute table column name |                                       |
| ------------------------------------ |---------------------------------------|
| OSA_CAMPANHA                         | year                                  |
| OSA_ID                               |                                       |
| OSA_NUM                              |                                       |
| OSA_AREA                             | area (in sq m)                        |
| PAR_ID                               |                                       |
| CAT_OCU_SIGLA                        | vague surface usage (abbreviation)    |
| CAT_OCU_DESCR                        | vague surface usage                   |
| CLA_OCU_SIGLA                        | type of surface covering (abbreviation) |
| **CLA_OCU_DESCR**                    | type of surface covering              |
| ARV_NUM_OLIV                         |                                       |
| ARV_NUM_OLIV_30                      |                                       |
| ARV_NUM_CASFR                        |                                       |
| ARV_NUM_CASFR_60                     |                                       |
| PUN_CUL                              | three digit numerical code (likely related to CLA_OCU_DESCR) |

## Available years
2017, 2018, 2019, 2020, 2021

## Largest classes and stats
(Disclaimer: Multiple crop classes for several parcels. We only included the first one in the harmonisation.)

Data from 2021:

217 different classes

70,422 unique parcels