# VSRR - Provisional monthly number of live births by state

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vsrr-provisional-monthly-number-of-live-births-by-state) |
| Metadata | [Link](https://data.cdc.gov/api/views/hdcd-69iu) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/hdcd-69iu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/hdcd-69iu/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | hdcd-69iu |
| Name | VSRR - Provisional monthly number of live births by state |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | live births |
| Created | 2017-01-18T15:32:41Z |
| Publication Date | 2017-02-27T14:41:53Z |

## Description

https://www.cdc.gov/nchs/products/vsrr/provisional-tables.htm 

Monthly provisional counts of births are provided by state of residence (50 states, District of Columbia and Puerto Rico). Provisional counts of births are based on data received and processed by the National Center for Health Statistics (NCHS) as of a specified date and may be updated during the course of a data year.

NOTE: Figures include all revisions received from the states and, therefore, may differ from those previously published. Data are provisional and are subject to monthly reporting variation. Provisional counts may differ by up to 5% or more from final counts, and the accuracy of the provisional counts may change over time. Data are estimates by state of residence. For discussion of the nature, source, and limitations of the data, see "Technical Notes" of the report, Births, Marriages, Divorces, and Deaths: Provisional Data for 2009. Available from URL: https://www.cdc.gov/nchs/data/nvsr/nvsr58/nvsr58_25.htm. Final counts of births and deaths for previous years can be obtained from http://wonder.cdc.gov.

SOURCE: Provisional data from the National Vital Statistics System, National Center for Health Statistics, CDC.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type | Render Type |
| ======== | ============== | ================================= | ================================= | ========= | =========== |
| Yes      | series tag     | state                             | State                             | text      | text        |
| No       |                | year                              | Year                              | number    | text        |
| No       |                | month                             | Month                             | text      | text        |
| Yes      | numeric metric | provisional_number_of_live_births | Provisional Number of Live Births | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:hdcd-69iu d:2016-01-01T00:00:00.000Z t:state=ALABAMA m:provisional_number_of_live_births=4816

series e:hdcd-69iu d:2016-02-01T00:00:00.000Z t:state=ALABAMA m:provisional_number_of_live_births=4690

series e:hdcd-69iu d:2016-03-01T00:00:00.000Z t:state=ALABAMA m:provisional_number_of_live_births=4847
```

## Meta Commands

```ls
metric m:provisional_number_of_live_births p:integer l:"Provisional Number of Live Births" t:dataTypeName=number

entity e:hdcd-69iu l:"VSRR - Provisional monthly number of live births by state" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/hdcd-69iu

property e:hdcd-69iu t:meta.view v:id=hdcd-69iu v:category=NCHS v:attributionLink=https://www.cdc.gov/nchs/products/vsrr/provisional-tables.htm v:averageRating=0 v:name="VSRR - Provisional monthly number of live births by state" v:attribution="National Center for Health Statistics"

property e:hdcd-69iu t:meta.view.license v:name="Public Domain"

property e:hdcd-69iu t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:hdcd-69iu t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:hdcd-69iu t:meta.view.metadata.custom_fields.common_core v:Contact_Email=hku4@cdc.gov v:Publisher="National Center for Health Statistics" v:Contact_Name=NCHS v:Bureau_Code=009:000 v:Program_Code=009:020
```

## Top Records

```ls
| state   | year | month     | provisional_number_of_live_births | 
| ======= | ==== | ========= | ================================= | 
| ALABAMA | 2016 | January   | 4816                              | 
| ALABAMA | 2016 | February  | 4690                              | 
| ALABAMA | 2016 | March     | 4847                              | 
| ALABAMA | 2016 | April     | 4536                              | 
| ALABAMA | 2016 | May       | 4789                              | 
| ALABAMA | 2016 | June      | 5057                              | 
| ALABAMA | 2016 | July      | 5038                              | 
| ALABAMA | 2016 | August    | 5331                              | 
| ALABAMA | 2016 | September | 5242                              | 
| ALASKA  | 2016 | January   | 943                               | 
```