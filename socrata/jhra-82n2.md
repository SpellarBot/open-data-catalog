# ARR Household Hazardous Waste Monthly Materials Collection Weight Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arr-household-hazardous-waste-monthly-materials-collection-weight-report) |
| Metadata | [Link](https://data.austintexas.gov/api/views/jhra-82n2) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/jhra-82n2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/jhra-82n2/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | jhra-82n2 |
| Name | ARR Household Hazardous Waste Monthly Materials Collection Weight Report |
| Tags | household, hazardous, waste, resource recovery, recycle |
| Created | 2015-09-14T18:17:23Z |
| Publication Date | 2015-09-15T18:24:30Z |

## Description

Data indicating each type and weight of material collected at the Household Hazardous Waste facility for fiscal year 2015.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | material    | Material   | text      | text        |
| Yes      | numeric metric | oct_14      | Oct-14     | number    | number      |
| Yes      | numeric metric | nov_14      | Nov-14     | number    | number      |
| Yes      | numeric metric | dec_14      | Dec-14     | number    | number      |
| Yes      | numeric metric | jan_15      | Jan-15     | number    | number      |
| Yes      | numeric metric | feb_15      | Feb-15     | number    | number      |
| Yes      | numeric metric | mar_15      | Mar-15     | number    | number      |
| Yes      | numeric metric | apr_15      | Apr-15     | number    | number      |
| Yes      | numeric metric | may_15      | May-15     | number    | number      |
| Yes      | numeric metric | jun_15      | Jun-15     | number    | number      |
| Yes      | numeric metric | jul_15      | Jul-15     | number    | number      |
| Yes      | numeric metric | aug_15      | Aug-15     | number    | number      |
| Yes      | numeric metric | sep_15      | Sep-15     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jhra-82n2 d:2015-09-14T11:17:28.000Z t:material="Alkaline Batteries" m:nov_14=4040 m:jul_15=7567 m:oct_14=7319.2 m:may_15=10515 m:mar_15=10072.3 m:jan_15=6632.9 m:jun_15=23.4 m:feb_15=10862.5 m:dec_14=7309 m:apr_15=0

series e:jhra-82n2 d:2015-09-14T11:17:28.000Z t:material="Lithium Batteries" m:nov_14=51 m:jul_15=108 m:oct_14=211 m:may_15=74 m:mar_15=28 m:jan_15=120 m:jun_15=187 m:feb_15=201 m:dec_14=37 m:apr_15=276

series e:jhra-82n2 d:2015-09-14T11:17:28.000Z t:material="Lead Batteries" m:nov_14=2270 m:jul_15=7660 m:oct_14=2790 m:may_15=7210 m:mar_15=2810 m:jan_15=3280 m:jun_15=3580 m:feb_15=0 m:dec_14=619 m:apr_15=880
```

## Meta Commands

```ls
metric m:oct_14 p:float l:Oct-14 t:dataTypeName=number

metric m:nov_14 p:float l:Nov-14 t:dataTypeName=number

metric m:dec_14 p:float l:Dec-14 t:dataTypeName=number

metric m:jan_15 p:float l:Jan-15 t:dataTypeName=number

metric m:feb_15 p:float l:Feb-15 t:dataTypeName=number

metric m:mar_15 p:float l:Mar-15 t:dataTypeName=number

metric m:apr_15 p:float l:Apr-15 t:dataTypeName=number

metric m:may_15 p:float l:May-15 t:dataTypeName=number

metric m:jun_15 p:float l:Jun-15 t:dataTypeName=number

metric m:jul_15 p:float l:Jul-15 t:dataTypeName=number

metric m:aug_15 p:float l:Aug-15 t:dataTypeName=number

metric m:sep_15 p:float l:Sep-15 t:dataTypeName=number

entity e:jhra-82n2 l:"ARR Household Hazardous Waste Monthly Materials Collection Weight Report" t:url=https://data.austintexas.gov/api/views/jhra-82n2

property e:jhra-82n2 t:meta.view v:id=jhra-82n2 v:averageRating=0 v:name="ARR Household Hazardous Waste Monthly Materials Collection Weight Report"

property e:jhra-82n2 t:meta.view.owner v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:displayName=erin.benoit@austintexas.gov

property e:jhra-82n2 t:meta.view.tableauthor v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:roleName=editor v:displayName=erin.benoit@austintexas.gov
```

## Top Records

```ls
| :updated_at | material               | oct_14 | nov_14 | dec_14 | jan_15 | feb_15  | mar_15  | apr_15 | may_15 | jun_15  | jul_15 | aug_15 | sep_15 | 
| =========== | ====================== | ====== | ====== | ====== | ====== | ======= | ======= | ====== | ====== | ======= | ====== | ====== | ====== | 
| 1442229448  | Alkaline Batteries     | 7319.2 | 4040   | 7309   | 6632.9 | 10862.5 | 10072.3 | 0      | 10515  | 23.4    | 7567   |        |        | 
| 1442229448  | Lithium Batteries      | 211    | 51     | 37     | 120    | 201     | 28      | 276    | 74     | 187     | 108    |        |        | 
| 1442229448  | Lead Batteries         | 2790   | 2270   | 619    | 3280   | 0       | 2810    | 880    | 7210   | 3580    | 7660   |        |        | 
| 1442229448  | Rechargeable Batteries | 1980   | 0      | 2703.5 | 2381   | 2694    | 2073    | 1710   | 0      | 0       | 0      |        |        | 
| 1442229448  | Lightbulbs             | 839.9  | 535    | 1056.2 | 1555.8 | 1152    | 1277    | 839.8  | 1164   | 18      | 3339.2 |        |        | 
| 1442229448  | Ballast                | 0      | 0      | 391    | 0      | 0       | 523     | 0      | 0      | 0       | 440    |        |        | 
| 1442229448  | Oil                    | 4927.5 | 3832.5 | 6037.5 | 5265   | 9037.5  | 5640    | 5872.5 | 7162.5 | 6435.00 | 7185   |        |        | 
| 1442229448  | Oil Filters            | 350    | 275    | 275    | 275    | 275     | 275     | 825    | 0      | 0       | 525    |        |        | 
| 1442229448  | Antifreeze             | 4035   | 0      | 0      | 0      | 2190    | 0       | 0      | 4897.5 | 0       | 4500   |        |        | 
| 1442229448  | Cooking Oil            | 3825   | 0      | 1875   | 2400   | 2250    | 1125    | 0      | 0      | 0       | 1125   |        |        | 
```