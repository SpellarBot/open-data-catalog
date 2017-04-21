# Illinois Tuberculosis Cases By County, 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/illinois-tuberculosis-cases-by-county-2010-a517e) |
| Metadata | [Link](https://data.illinois.gov/api/views/4hqd-5b3x) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/4hqd-5b3x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/4hqd-5b3x/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 4hqd-5b3x |
| Name | Illinois Tuberculosis Cases By County, 2010 |
| Attribution | Illinois Department of Public Health, Office of Health Protection, Division of Infectious Disease, Tuberculosis Control Section |
| Category | Health |
| Tags | health, disease, tuberculosis, tb, infectious disease |
| Created | 2014-08-11T20:35:25Z |
| Publication Date | 2014-08-11T20:36:25Z |

## Description

Data was provided by the Tuberculosis Control Section of the Office of Health Protection's Division of Infectious Diseases.

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | county     | County | text      | text        |
| Yes      | numeric metric | 2010       | 2010   | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4hqd-5b3x d:2010-01-01T00:00:00.000Z t:county=Adams m:2010=0

series e:4hqd-5b3x d:2010-01-01T00:00:00.000Z t:county=Alexander m:2010=0

series e:4hqd-5b3x d:2010-01-01T00:00:00.000Z t:county=Bond m:2010=0
```

## Meta Commands

```ls
metric m:2010 p:integer l:2010 t:dataTypeName=number

entity e:4hqd-5b3x l:"Illinois Tuberculosis Cases By County, 2010" t:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Infectious Disease, Tuberculosis Control Section" t:url=https://data.illinois.gov/api/views/4hqd-5b3x

property e:4hqd-5b3x t:meta.view v:id=4hqd-5b3x v:category=Health v:averageRating=0 v:name="Illinois Tuberculosis Cases By County, 2010" v:attribution="Illinois Department of Public Health, Office of Health Protection, Division of Infectious Disease, Tuberculosis Control Section"

property e:4hqd-5b3x t:meta.view.license v:name="Public Domain"

property e:4hqd-5b3x t:meta.view.owner v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"

property e:4hqd-5b3x t:meta.view.tableauthor v:id=pf5f-nyht v:screenName="Kathryn M" v:displayName="Kathryn M"
```

## Top Records

```ls
| county    | 2010 | 
| ========= | ==== | 
| Adams     | 0    | 
| Alexander | 0    | 
| Bond      | 0    | 
| Boone     | 0    | 
| Brown     | 0    | 
| Bureau    | 0    | 
| Calhoun   | 0    | 
| Carroll   | 1    | 
| Cass      | 0    | 
| Champaign | 5    | 
```