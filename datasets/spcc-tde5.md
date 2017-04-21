# VSRR - Provisional monthly number of deaths by state

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vsrr-provisional-monthly-number-of-deaths-by-state) |
| Metadata | [Link](https://data.cdc.gov/api/views/spcc-tde5) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/spcc-tde5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/spcc-tde5/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | spcc-tde5 |
| Name | VSRR - Provisional monthly number of deaths by state |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | deaths, infant deaths |
| Created | 2017-01-18T15:22:01Z |
| Publication Date | 2017-02-27T14:45:56Z |

## Description

https://www.cdc.gov/nchs/products/vsrr/provisional-tables.htm 

Monthly provisional counts of deaths and infant deaths are provided by state of residence (50 states, District of Columbia and Puerto Rico). Provisional counts of deaths and infant deaths are based on data received and processed by the National Center for Health Statistics (NCHS) as of a specified date and may be updated during the course of a data year.

NOTES: Figures include all revisions received from the states and, therefore, may differ from those previously published. Data are provisional and are subject to monthly reporting variation. National data are calculated by summing the number of events reported by state of residence; counts are rounded to the nearest thousand (births and deaths) or hundred (infant deaths). Provisional counts may differ by approximately 2% from final counts, due to rounding and reporting variation. Additionally, the accuracy of the provisional counts may change over time. For discussion of the nature, source, and limitations of the data, see "Technical Notes" of the report, Births, Marriages, Divorces, and Deaths: Provisional Data for 2009. Available from URL: http://www.cdc.gov/nchs/data/nvsr/nvsr58/nvsr58_25.htm. Final counts of births, deaths, and infant deaths for previous years can be obtained from http://wonder.cdc.gov.

SOURCE: Provisional data from the National Vital Statistics System, National Center for Health Statistics, CDC.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | state                        | State                        | text      | text        |
| No       |                | year                         | Year                         | number    | text        |
| No       |                | month                        | Month                        | text      | text        |
| Yes      | numeric metric | provisional_number_of_deaths | Provisional Number of Deaths | number    | number      |
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
series e:spcc-tde5 d:2016-01-01T00:00:00.000Z t:state=ALABAMA m:provisional_number_of_deaths=4633

series e:spcc-tde5 d:2016-02-01T00:00:00.000Z t:state=ALABAMA m:provisional_number_of_deaths=4451

series e:spcc-tde5 d:2016-03-01T00:00:00.000Z t:state=ALABAMA m:provisional_number_of_deaths=4583
```

## Meta Commands

```ls
metric m:provisional_number_of_deaths p:integer l:"Provisional Number of Deaths" t:dataTypeName=number

entity e:spcc-tde5 l:"VSRR - Provisional monthly number of deaths by state" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/spcc-tde5

property e:spcc-tde5 t:meta.view v:id=spcc-tde5 v:category=NCHS v:attributionLink=https://www.cdc.gov/nchs/products/vsrr/provisional-tables.htm v:averageRating=0 v:name="VSRR - Provisional monthly number of deaths by state" v:attribution="National Center for Health Statistics"

property e:spcc-tde5 t:meta.view.license v:name="Public Domain"

property e:spcc-tde5 t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:spcc-tde5 t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:spcc-tde5 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=hku4@cdc.gov v:Publisher="National Center for Health Statistics" v:Contact_Name=NCHS v:Bureau_Code=009:000 v:Program_Code=009:020
```

## Top Records

```ls
| state   | year | month     | provisional_number_of_deaths | 
| ======= | ==== | ========= | ============================ | 
| ALABAMA | 2016 | January   | 4633                         | 
| ALABAMA | 2016 | February  | 4451                         | 
| ALABAMA | 2016 | March     | 4583                         | 
| ALABAMA | 2016 | April     | 4250                         | 
| ALABAMA | 2016 | May       | 4238                         | 
| ALABAMA | 2016 | June      | 4076                         | 
| ALABAMA | 2016 | July      | 4193                         | 
| ALABAMA | 2016 | August    | 4171                         | 
| ALABAMA | 2016 | September | 4076                         | 
| ALASKA  | 2016 | January   | 391                          | 
```