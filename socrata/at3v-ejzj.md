# Table 12: Wastewater Treatment Plant Operations & Compliance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-12-wastewater-treatment-plant-operations-compliance-c7d2c) |
| Metadata | [Link](https://data.hawaii.gov/api/views/at3v-ejzj) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/at3v-ejzj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/at3v-ejzj/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | at3v-ejzj |
| Name | Table 12: Wastewater Treatment Plant Operations & Compliance |
| Attribution | DOH |
| Category | Health |
| Tags | wastewater, treatment, plant |
| Created | 2012-08-01T00:04:07Z |
| Publication Date | 2012-08-01T00:04:54Z |

## Description

DOH Environmental Indicators

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| No       |                | _                                     | #                                     | number    | number      |
| Yes      | time           | calendar_year                         | Calendar Year                         | number    | text        |
| Yes      | numeric metric | total_number_of_plants                | Total Number of Plants                | number    | number      |
| Yes      | numeric metric | number_of_plants_inspected            | Number of Plants Inspected            | number    | number      |
| Yes      | numeric metric | number_of_plants_rated_unsatisfactory | Number of Plants Rated Unsatisfactory | number    | number      |
| Yes      | numeric metric | percentage_in_compliance              | Percentage in Compliance              | percent   | percent     |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _
```

## Data Commands

```ls
series e:at3v-ejzj d:2006-01-01T00:00:00.000Z m:percentage_in_compliance=92 m:total_number_of_plants=180 m:number_of_plants_inspected=93 m:number_of_plants_rated_unsatisfactory=14

series e:at3v-ejzj d:2007-01-01T00:00:00.000Z m:percentage_in_compliance=82 m:total_number_of_plants=180 m:number_of_plants_inspected=102 m:number_of_plants_rated_unsatisfactory=33

series e:at3v-ejzj d:2008-01-01T00:00:00.000Z m:percentage_in_compliance=92 m:total_number_of_plants=180 m:number_of_plants_inspected=34 m:number_of_plants_rated_unsatisfactory=15
```

## Meta Commands

```ls
metric m:total_number_of_plants p:integer l:"Total Number of Plants" t:dataTypeName=number

metric m:number_of_plants_inspected p:integer l:"Number of Plants Inspected" t:dataTypeName=number

metric m:number_of_plants_rated_unsatisfactory p:integer l:"Number of Plants Rated Unsatisfactory" t:dataTypeName=number

metric m:percentage_in_compliance p:integer l:"Percentage in Compliance" t:dataTypeName=percent

entity e:at3v-ejzj l:"Table 12: Wastewater Treatment Plant Operations & Compliance" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/at3v-ejzj

property e:at3v-ejzj t:meta.view v:id=at3v-ejzj v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Table 12: Wastewater Treatment Plant Operations & Compliance" v:attribution=DOH

property e:at3v-ejzj t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:at3v-ejzj t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:at3v-ejzj t:meta.view.tableauthor v:id=8c9u-vteh v:screenName=lorrink v:roleName=editor v:displayName=lorrink
```

## Top Records

```ls
| _ | calendar_year | total_number_of_plants | number_of_plants_inspected | number_of_plants_rated_unsatisfactory | percentage_in_compliance | 
| = | ============= | ====================== | ========================== | ===================================== | ======================== | 
| 1 | 2006          | 180                    | 93                         | 14                                    | 92                       | 
| 2 | 2007          | 180                    | 102                        | 33                                    | 82                       | 
| 4 | 2008          | 180                    | 34                         | 15                                    | 92                       | 
| 5 | 2009          | 180                    | 119                        | 38                                    | 79                       | 
| 6 | 2010          | 180                    | 114                        | 13                                    | 93                       | 
```