# Selected Trend Table from Health, United States, 2011. Leading causes of death and numbers of deaths, by sex, race, and Hispanic origin: United States, 1980 and 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/selected-trend-table-from-health-united-states-2011-leading-causes-of-death-and-numbers-of) |
| Metadata | [Link](https://data.cdc.gov/api/views/vp9c-m6nq) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/vp9c-m6nq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/vp9c-m6nq/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | vp9c-m6nq |
| Name | Selected Trend Table from Health, United States, 2011. Leading causes of death and numbers of deaths, by sex, race, and Hispanic origin: United States, 1980 and 2009 |
| Attribution | Health, United States |
| Category | Health Statistics |
| Tags | hus, cause of death |
| Created | 2013-07-29T20:03:23Z |
| Publication Date | 2013-07-29T20:04:19Z |

## Description

Health, United States is an annual report on trends in health statistics, find more information at http://www.cdc.gov/nchs/hus.htm.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | numeric metric | rank_order     | Rank order     | number    | number      |
| Yes      | series tag     | group          | Group          | text      | text        |
| Yes      | time           | year           | Year           | number    | number      |
| Yes      | series tag     | cause_of_death | Cause of death | text      | text        |
| Yes      | numeric metric | flag           | Flag           | number    | number      |
| Yes      | numeric metric | deaths         | Deaths         | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vp9c-m6nq d:1980-01-01T00:00:00.000Z t:cause_of_death="All causes" t:group="All persons" m:deaths=1989841

series e:vp9c-m6nq d:1980-01-01T00:00:00.000Z t:cause_of_death="Diseases of heart" t:group="All persons" m:deaths=761085 m:rank_order=1

series e:vp9c-m6nq d:1980-01-01T00:00:00.000Z t:cause_of_death="Malignant neoplasms" t:group="All persons" m:deaths=416509 m:rank_order=2
```

## Meta Commands

```ls
metric m:rank_order p:integer l:"Rank order" t:dataTypeName=number

metric m:flag p:integer l:Flag t:dataTypeName=number

metric m:deaths p:integer l:Deaths t:dataTypeName=number

entity e:vp9c-m6nq l:"Selected Trend Table from Health, United States, 2011. Leading causes of death and numbers of deaths, by sex, race, and Hispanic origin: United States, 1980 and 2009" t:attribution="Health, United States" t:url=https://data.cdc.gov/api/views/vp9c-m6nq

property e:vp9c-m6nq t:meta.view v:id=vp9c-m6nq v:category="Health Statistics" v:attributionLink=http://www.cdc.gov/nchs/hus.htm v:averageRating=0 v:name="Selected Trend Table from Health, United States, 2011. Leading causes of death and numbers of deaths, by sex, race, and Hispanic origin: United States, 1980 and 2009" v:attribution="Health, United States"

property e:vp9c-m6nq t:meta.view.owner v:id=vr5q-rutf v:screenName=SFranco v:displayName=SFranco

property e:vp9c-m6nq t:meta.view.tableauthor v:id=g3fc-zmqn v:profileImageUrlMedium=/api/users/g3fc-zmqn/profile_images/THUMB v:profileImageUrlLarge=/api/users/g3fc-zmqn/profile_images/LARGE v:screenName=CDC v:profileImageUrlSmall=/api/users/g3fc-zmqn/profile_images/TINY v:roleName=publisher v:displayName=CDC

property e:vp9c-m6nq t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| rank_order | group       | year | cause_of_death                         | flag | deaths  | 
| ========== | =========== | ==== | ====================================== | ==== | ======= | 
|            | All persons | 1980 | All causes                             |      | 1989841 | 
| 1          | All persons | 1980 | Diseases of heart                      |      | 761085  | 
| 2          | All persons | 1980 | Malignant neoplasms                    |      | 416509  | 
| 3          | All persons | 1980 | Cerebrovascular diseases               |      | 170225  | 
| 4          | All persons | 1980 | Unintentional injuries                 |      | 105718  | 
| 5          | All persons | 1980 | Chronic obstructive pulmonary diseases |      | 56050   | 
| 6          | All persons | 1980 | Pneumonia and influenza                |      | 54619   | 
| 7          | All persons | 1980 | Diabetes mellitus                      |      | 34851   | 
| 8          | All persons | 1980 | Chronic liver disease and cirrhosis    |      | 30583   | 
| 9          | All persons | 1980 | Atherosclerosis                        |      | 29449   | 
```