# Plant Pathogen

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/plant-pathogen-6fa93) |
| Metadata | [Link](https://data.oregon.gov/api/views/2uq2-u3ct) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/2uq2-u3ct/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/2uq2-u3ct/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 2uq2-u3ct |
| Name | Plant Pathogen |
| Attribution | Oregon Department of Agriculture |
| Category | Natural Resources |
| Tags | plant, health, pathogen, laboratory, fungi, bacteria |
| Created | 2014-03-04T16:27:44Z |
| Publication Date | 2014-08-08T19:13:28Z |

## Description

Plant pathogen list from the Oregon Department of Agriculture, Plant Health Laboratory.

## Columns

```ls
| Included | Schema Type | Field Name       | Name       | Data Type | Render Type |
| ======== | =========== | ================ | ========== | ========= | =========== |
| No       | time        | :updated_at      | updated_at | meta_data | meta_data   |
| Yes      | series tag  | type             | Type       | text      | text        |
| Yes      | series tag  | photo            | Photo      | photo     | photo       |
| Yes      | series tag  | more_information | Disease    | url       | url         |
| Yes      | series tag  | pathogen         | Pathogen   | html      | html        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2uq2-u3ct d:2014-07-16T14:35:29.000Z t:pathogen="Meloidogyne chitwoodii" t:more_information=http://www.oregon.gov/oda/shared/Documents/Publications/PlantHealth/ColumbiaRootKnotNematode.pdf t:type=Nematode t:photo=IjaJ49tKHVS_8FqfiVt6tqjL_wnmsRM4Dd_p6RyoSoM m:row_number.2uq2-u3ct=1

series e:2uq2-u3ct d:2014-07-16T14:36:01.000Z t:pathogen="Globodera pallida" t:more_information=http://www.oregon.gov/oda/shared/Documents/Publications/PlantHealth/PalePotatoCystNematode.pdf t:type=Nematode t:photo=4B1KGYJNVPf-W2LbfbV4OwS7ZTHZEmGKUSWqGbW8Oh4 m:row_number.2uq2-u3ct=2

series e:2uq2-u3ct d:2014-07-16T14:36:49.000Z t:pathogen="Globodera rostochiensis" t:more_information=http://www.oregon.gov/oda/shared/Documents/Publications/PlantHealth/GoldenPotatoCystNematode.pdf t:type=Nematode t:photo=cyFdu-dkPo6n1UJAEFRfnQl7RHV9Mk-f8Zyr80nwX-c m:row_number.2uq2-u3ct=3
```

## Meta Commands

```ls
metric m:row_number.2uq2-u3ct p:long l:"Row Number"

entity e:2uq2-u3ct l:"Plant Pathogen" t:attribution="Oregon Department of Agriculture" t:url=https://data.oregon.gov/api/views/2uq2-u3ct

property e:2uq2-u3ct t:meta.view v:id=2uq2-u3ct v:category="Natural Resources" v:attributionLink=http://oregon.gov/ODA v:averageRating=0 v:name="Plant Pathogen" v:attribution="Oregon Department of Agriculture"

property e:2uq2-u3ct t:meta.view.owner v:id=hfyt-zc65 v:screenName="Katherine Leamaster" v:displayName="Katherine Leamaster"

property e:2uq2-u3ct t:meta.view.tableauthor v:id=hfyt-zc65 v:screenName="Katherine Leamaster" v:displayName="Katherine Leamaster"
```

## Top Records

```ls
| :updated_at | type        | photo                                       | more_information                                                                                                                  | pathogen                                                               | 
| =========== | =========== | =========================================== | ================================================================================================================================= | ====================================================================== | 
| 1405521329  | Nematode    | IjaJ49tKHVS_8FqfiVt6tqjL_wnmsRM4Dd_p6RyoSoM | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantHealth/ColumbiaRootKnotNematode.pdf, Columbia root knot nematode]   | Meloidogyne chitwoodii                                                 | 
| 1405521361  | Nematode    | 4B1KGYJNVPf-W2LbfbV4OwS7ZTHZEmGKUSWqGbW8Oh4 | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantHealth/PalePotatoCystNematode.pdf, Pale potato cyst nematode]       | Globodera pallida                                                      | 
| 1405521409  | Nematode    | cyFdu-dkPo6n1UJAEFRfnQl7RHV9Mk-f8Zyr80nwX-c | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantHealth/GoldenPotatoCystNematode.pdf, Golden potato cyst nematode]   | Globodera rostochiensis                                                | 
| 1407495031  | Phytoplasma | q2Ee4GlOWjV_SWYXqrBkOFY2CwV27mOmPbwCUwKdXa8 | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantHealth/PeachXdisease.pdf, Peach X-disease]                          | Peach X-disease phytoplasma                                            | 
| 1407495039  | Phytoplasma | 5280bR2Xo5hdVhnQnt4OQSoIXnz4lkrhOdFHHx0Djdw | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantHealth/PeachRosette.pdf, Peach rosette]                             | Peach rosette phytoplasma                                              | 
| 1407495048  | Phytoplasma | leUk0QEMC5dFV-Pq6S6vjpfxna8_qQ5uL2blKbz8P7s | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantHealth/ElmPhloem.pdf, Elm phloem necrosis]                          | Elm phloem necrosiphytoplasma                                          | 
| 1407495056  | Bateria     | QRNYwvivyoVOiGI6vaRA369L2Te0uFO88lyvhgwjuWU | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantHealth/BacterialWiltBeans.pdf, Bacterial wilt of beans]             | Curtobacterium flaccumfaciens pv. flaccumfaciens                       | 
| 1407495066  | Bateria     | XcRkUn2zSTdTaUJD6RlgpHAOnfMdrjAjfQYvRayDvzg | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantHealth/BeanCommonBacterial.pdf, Bean common bacterial blight]       | Xanthomonas campestris pv. Phaseoli, Xanthomonas fuscans subsp. Fuscan | 
| 1407495073  | Bateria     | RLcIbZY2OIQI75nG8JHIsYsH2QGNFw-jqkOF_TYEI-0 | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantHealth/HaloBlightBeans.pdf, Halo blights of beans]                  | Pseudomonas syringae pv. phaseolicola                                  | 
| 1407495081  | Bateria     | juMQ7Nw5vQdh4z4FjSxrPmtzkqT1tKwhsxOtPazhTYE | [http://www.oregon.gov/oda/shared/Documents/Publications/PlantHealth/BacterialBrownSpotBeans.pdf, Bacterial brown spots of beans] | Pseudomonas syringae pv. syringae                                      | 
```