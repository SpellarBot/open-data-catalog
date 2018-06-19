# Hawaii's Petroleum Use by Sector (Source: US Energy Information Administration)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaiis-petroleum-use-gallons-by-sector-source-dbedt-da3db) |
| Metadata | [Link](https://data.hawaii.gov/api/views/tbh8-drn6) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/tbh8-drn6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/tbh8-drn6/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | tbh8-drn6 |
| Name | Hawaii's Petroleum Use by Sector (Source: US Energy Information Administration) |
| Created | 2014-05-30T19:02:09Z |
| Publication Date | 2016-11-23T18:38:29Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | sector      | Sector     | text      | text        |
| Yes      | numeric metric | percentage  | Percentage | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tbh8-drn6 d:2016-11-23T18:35:23.000Z t:sector="Electric Power" m:percentage=26

series e:tbh8-drn6 d:2016-11-23T18:35:41.000Z t:sector=Commercial m:percentage=2

series e:tbh8-drn6 d:2016-11-23T18:35:50.000Z t:sector=Industrial m:percentage=9
```

## Meta Commands

```ls
metric m:percentage p:integer l:Percentage t:dataTypeName=percent

entity e:tbh8-drn6 l:"Hawaii's Petroleum Use by Sector (Source: US Energy Information Administration)" t:url=https://data.hawaii.gov/api/views/tbh8-drn6

property e:tbh8-drn6 t:meta.view v:id=tbh8-drn6 v:averageRating=0 v:name="Hawaii's Petroleum Use by Sector (Source: US Energy Information Administration)"

property e:tbh8-drn6 t:meta.view.owner v:id=vf6n-ptiq v:screenName=Kathy v:displayName=Kathy

property e:tbh8-drn6 t:meta.view.tableauthor v:id=vf6n-ptiq v:screenName=Kathy v:roleName=publisher v:displayName=Kathy
```

## Top Records

```ls
| :updated_at | sector                | percentage | 
| =========== | ===================== | ========== | 
| 1479926123  | Electric Power        | 26         | 
| 1479926141  | Commercial            | 2          | 
| 1479926150  | Industrial            | 9          | 
| 1479926174  | Residential           | 1          | 
| 1479926185  | Air Transportation    | 31         | 
| 1479926198  | Marine Transportation | 3          | 
| 1479926240  | Ground Transportation | 28         | 
```