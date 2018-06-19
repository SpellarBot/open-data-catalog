# Hawaii's Electricity Production by Source (Source: EIA)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaiis-electricity-production-by-source-source-eia-e255a) |
| Metadata | [Link](https://data.hawaii.gov/api/views/it4c-kd85) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/it4c-kd85/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/it4c-kd85/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | it4c-kd85 |
| Name | Hawaii's Electricity Production by Source (Source: EIA) |
| Created | 2014-01-15T19:40:17Z |
| Publication Date | 2016-11-23T18:53:03Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | numeric metric | percentage  | Percentage | percent   | percent     |
| Yes      | series tag     | source      | Source     | text      | text        |
| Yes      | numeric metric | percent     | Percent    | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:it4c-kd85 d:2016-11-23T18:51:06.000Z t:source=Oil m:percent=67.9

series e:it4c-kd85 d:2016-11-23T18:51:16.000Z t:source=Coal m:percent=14.8

series e:it4c-kd85 d:2016-11-23T18:51:34.000Z t:source=Other m:percent=4.6
```

## Meta Commands

```ls
metric m:percentage p:float l:Percentage t:dataTypeName=percent

metric m:percent p:float l:Percent t:dataTypeName=percent

entity e:it4c-kd85 l:"Hawaii's Electricity Production by Source (Source: EIA)" t:url=https://data.hawaii.gov/api/views/it4c-kd85

property e:it4c-kd85 t:meta.view v:id=it4c-kd85 v:averageRating=0 v:name="Hawaii's Electricity Production by Source (Source: EIA)"

property e:it4c-kd85 t:meta.view.owner v:id=vf6n-ptiq v:screenName=Kathy v:displayName=Kathy

property e:it4c-kd85 t:meta.view.tableauthor v:id=vf6n-ptiq v:screenName=Kathy v:roleName=publisher v:displayName=Kathy
```

## Top Records

```ls
| :updated_at | percentage | source        | percent | 
| =========== | ========== | ============= | ======= | 
| 1479927066  |            | Oil           | 67.9    | 
| 1479927076  |            | Coal          | 14.8    | 
| 1479927094  |            | Other         | 4.6     | 
| 1479927101  |            | Wind          | 5.7     | 
| 1479927107  |            | Biomass       | 3.3     | 
| 1479927114  |            | Geothermal    | 2.5     | 
| 1479927122  |            | Hydroelectric | 0.9     | 
| 1479927138  |            | Solar         | 0.38    | 
```