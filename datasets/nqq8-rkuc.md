# VSRR - Provisional monthly and 12-month ending number of live births, deaths and infant deaths: United States

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vsrr-provisional-monthly-and-12-month-ending-number-of-live-births-deaths-and-infant-death) |
| Metadata | [Link](https://data.cdc.gov/api/views/nqq8-rkuc) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/nqq8-rkuc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/nqq8-rkuc/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | nqq8-rkuc |
| Name | VSRR - Provisional monthly and 12-month ending number of live births, deaths and infant deaths: United States |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | live births, deaths, infant deaths |
| Created | 2017-01-18T15:12:53Z |
| Publication Date | 2017-02-27T14:40:28Z |

## Description

https://www.cdc.gov/nchs/products/vsrr/provisional-tables.htm


Monthly and 12 month-ending provisional counts of births, deaths and infant deaths are provided for the United States. Provisional counts of births, deaths, and infant deaths are based on data received and processed by the National Center for Health Statistics (NCHS) as of a specified date and may be updated during the course of a data year.


NOTES: Figures include all revisions received from the states and, therefore, may differ from those previously published. Data are provisional and are subject to monthly reporting variation. National data are calculated by summing the number of events reported by state of residence; counts are rounded to the nearest thousand (births and deaths) or hundred (infant deaths). Provisional counts may differ by approximately 2% from final counts, due to rounding and reporting variation. Additionally, the accuracy of the provisional counts may change over time. For discussion of the nature, source, and limitations of the data, see "Technical Notes" of the report, Births, Marriages, Divorces, and Deaths: Provisional Data for 2009. Available from URL: http://www.cdc.gov/nchs/data/nvsr/nvsr58/nvsr58_25.htm. Final counts of births, deaths, and infant deaths for previous years can be obtained from http://wonder.cdc.gov.


SOURCE: Provisional data from the National Vital Statistics System, National Center for Health Statistics, CDC.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       |                | year            | Year            | number    | text        |
| No       |                | month           | Month           | text      | text        |
| No       |                | data_value_type | Data Value Type | text      | text        |
| Yes      | numeric metric | data_value      | Data Value      | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = data_value_type,year,month
```

## Data Commands

```ls
series e:nqq8-rkuc d:2016-01-01T00:00:00.000Z m:data_value=317000

series e:nqq8-rkuc d:2016-01-01T00:00:00.000Z m:data_value=246000

series e:nqq8-rkuc d:2016-01-01T00:00:00.000Z m:data_value=1900
```

## Meta Commands

```ls
metric m:data_value p:integer l:"Data Value" t:dataTypeName=number

entity e:nqq8-rkuc l:"VSRR - Provisional monthly and 12-month ending number of live births, deaths and infant deaths: United States" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/nqq8-rkuc

property e:nqq8-rkuc t:meta.view v:id=nqq8-rkuc v:category=NCHS v:attributionLink=https://www.cdc.gov/nchs/products/vsrr/provisional-tables.htm v:averageRating=0 v:name="VSRR - Provisional monthly and 12-month ending number of live births, deaths and infant deaths: United States" v:attribution="National Center for Health Statistics"

property e:nqq8-rkuc t:meta.view.license v:name="Public Domain"

property e:nqq8-rkuc t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:nqq8-rkuc t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:nqq8-rkuc t:meta.view.metadata.custom_fields.common_core v:Contact_Email=hku4@cdc.gov v:Contact_Name=NCHS v:Bureau_Code=009:000 v:Program_Code=009:020
```

## Top Records

```ls
| year | month    | data_value_type                         | data_value | 
| ==== | ======== | ======================================= | ========== | 
| 2016 | January  | Number of Live Births                   | 317000     | 
| 2016 | January  | Number of Deaths                        | 246000     | 
| 2016 | January  | Number of Infant Deaths                 | 1900       | 
| 2016 | January  | 12 Month-ending Number of Live Births   | 3977000    | 
| 2016 | January  | 12 Month-ending Number of Deaths        | 2725000    | 
| 2016 | January  | 12 Month-ending Number of Infant Deaths | 23400      | 
| 2016 | February | Number of Live Births                   | 306000     | 
| 2016 | February | Number of Deaths                        | 229000     | 
| 2016 | February | Number of Infant Deaths                 | 1900       | 
| 2016 | February | 12 Month-ending Number of Live Births   | 3984000    | 
```