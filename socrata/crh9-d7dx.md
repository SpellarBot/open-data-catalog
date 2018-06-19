# Table 6: Number of Hawaiian Coastal Waters by Island (2006)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-6-number-of-hawaiian-coastal-waters-by-island-2006-62ae6) |
| Metadata | [Link](https://data.hawaii.gov/api/views/crh9-d7dx) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/crh9-d7dx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/crh9-d7dx/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | crh9-d7dx |
| Name | Table 6: Number of Hawaiian Coastal Waters by Island (2006) |
| Attribution | DOH |
| Category | Health |
| Tags | hawaiian, coastal, waters |
| Created | 2012-07-31T23:33:01Z |
| Publication Date | 2012-07-31T23:39:02Z |

## Description

DOH Environmental Indicators

## Columns

```ls
| Included | Schema Type    | Field Name                                          | Name                                                | Data Type | Render Type |
| ======== | ============== | =================================================== | =================================================== | ========= | =========== |
| Yes      | numeric metric | number                                              | Number                                              | number    | number      |
| Yes      | series tag     | island                                              | Island                                              | text      | text        |
| Yes      | numeric metric | number_of_coastal_waters                            | Number of Coastal Waters                            | number    | number      |
| Yes      | numeric metric | number_of_impaired_coastal_waters                   | Number of Impaired Coastal Waters                   | number    | number      |
| Yes      | numeric metric | percentage_of_impaired_coastal_waters_by_island     | Percentage of Impaired Coastal Waters by Island     | percent   | percent     |
| Yes      | series tag     | percentage_of_impared_coastal_waters_by_state_total | Percentage of Impared Coastal Waters by State Total | text      | text        |
```

## Time Field

```ls
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:crh9-d7dx d:2006-01-01T00:00:00.000Z t:percentage_of_impared_coastal_waters_by_state_total=15% t:island=Hawaii m:number=1 m:number_of_coastal_waters=89 m:number_of_impaired_coastal_waters=31 m:percentage_of_impaired_coastal_waters_by_island=35

series e:crh9-d7dx d:2006-01-01T00:00:00.000Z t:percentage_of_impared_coastal_waters_by_state_total=12% t:island=Kauai m:number=2 m:number_of_coastal_waters=81 m:number_of_impaired_coastal_waters=26 m:percentage_of_impaired_coastal_waters_by_island=32

series e:crh9-d7dx d:2006-01-01T00:00:00.000Z t:percentage_of_impared_coastal_waters_by_state_total=3% t:island=Lanai m:number=3 m:number_of_coastal_waters=17 m:number_of_impaired_coastal_waters=6 m:percentage_of_impaired_coastal_waters_by_island=35
```

## Meta Commands

```ls
metric m:number p:integer l:Number t:dataTypeName=number

metric m:number_of_coastal_waters p:integer l:"Number of Coastal Waters" t:dataTypeName=number

metric m:number_of_impaired_coastal_waters p:integer l:"Number of Impaired Coastal Waters" t:dataTypeName=number

metric m:percentage_of_impaired_coastal_waters_by_island p:integer l:"Percentage of Impaired Coastal Waters by Island" t:dataTypeName=percent

entity e:crh9-d7dx l:"Table 6: Number of Hawaiian Coastal Waters by Island (2006)" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/crh9-d7dx

property e:crh9-d7dx t:meta.view v:id=crh9-d7dx v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Table 6: Number of Hawaiian Coastal Waters by Island (2006)" v:attribution=DOH

property e:crh9-d7dx t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:crh9-d7dx t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:crh9-d7dx t:meta.view.tableauthor v:id=8c9u-vteh v:screenName=lorrink v:roleName=editor v:displayName=lorrink
```

## Top Records

```ls
| number | island  | number_of_coastal_waters | number_of_impaired_coastal_waters | percentage_of_impaired_coastal_waters_by_island | percentage_of_impared_coastal_waters_by_state_total | 
| ====== | ======= | ======================== | ================================= | =============================================== | =================================================== | 
| 1      | Hawaii  | 89                       | 31                                | 35                                              | 15%                                                 | 
| 2      | Kauai   | 81                       | 26                                | 32                                              | 12%                                                 | 
| 3      | Lanai   | 17                       | 6                                 | 35                                              | 3%                                                  | 
| 4      | Maui    | 122                      | 72                                | 59                                              | 34%                                                 | 
| 5      | Molokai | 37                       | 3                                 | 8                                               | 1%                                                  | 
| 6      | Oahu    | 176                      | 71                                | 40                                              | 34%                                                 | 
|        |         |                          |                                   |                                                 |                                                     | 
```