# Supplemental Security Income (SSI) Living Arrangements by Region: Beginning 2002

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/supplemental-security-income-ssi-living-arrangements-by-region-beginning-2002) |
| Metadata | [Link](https://data.ny.gov/api/views/iuu6-qurh) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/iuu6-qurh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/iuu6-qurh/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | iuu6-qurh |
| Name | Supplemental Security Income (SSI) Living Arrangements by Region: Beginning 2002 |
| Attribution | New York State Office of Temporary and Disability Assistance |
| Category | Human Services |
| Tags | ssi, supplemental security income, disability, disabled, blind, aged, ssi state supplement |
| Created | 2014-01-14T16:01:13Z |
| Publication Date | 2017-03-31T22:01:03Z |

## Description

These data are monthly listings of the number of recipients in each living arrangement classification in the Supplemental Security Income Program, by region.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       |                | year               | Year               | number    | number      |
| No       |                | month              | Month              | text      | text        |
| Yes      | series tag     | monthcode          | Month Code         | text      | number      |
| Yes      | series tag     | location           | Location           | text      | text        |
| Yes      | series tag     | living_arrangement | Living Arrangement | text      | text        |
| Yes      | numeric metric | recipients         | Recipients         | number    | number      |
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
series e:iuu6-qurh d:2014-07-01T00:00:00.000Z t:monthcode=7 t:location="Mental Hygiene" t:living_arrangement="Congregate Care Level 1" m:recipients=1852

series e:iuu6-qurh d:2014-07-01T00:00:00.000Z t:monthcode=7 t:location="Mental Hygiene" t:living_arrangement="Congregate Care Level 2" m:recipients=873

series e:iuu6-qurh d:2014-07-01T00:00:00.000Z t:monthcode=7 t:location="Mental Hygiene" t:living_arrangement="Congregate Care Level 3" m:recipients=1
```

## Meta Commands

```ls
metric m:recipients p:integer l:Recipients d:"Table 18 Supplemental Security Income Recipients." t:dataTypeName=number

entity e:iuu6-qurh l:"Supplemental Security Income (SSI) Living Arrangements by Region: Beginning 2002" t:attribution="New York State Office of Temporary and Disability Assistance" t:url=https://data.ny.gov/api/views/iuu6-qurh

property e:iuu6-qurh t:meta.view v:id=iuu6-qurh v:category="Human Services" v:attributionLink=http://otda.ny.gov/resources/caseload/ v:averageRating=0 v:name="Supplemental Security Income (SSI) Living Arrangements by Region: Beginning 2002" v:attribution="New York State Office of Temporary and Disability Assistance"

property e:iuu6-qurh t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:iuu6-qurh t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:iuu6-qurh t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | month | monthcode | location       | living_arrangement             | recipients | 
| ==== | ===== | ========= | ============== | ============================== | ========== | 
| 2014 | July  | 7         | Mental Hygiene | Congregate Care Level 1        | 1852       | 
| 2014 | July  | 7         | Mental Hygiene | Congregate Care Level 2        | 873        | 
| 2014 | July  | 7         | Mental Hygiene | Congregate Care Level 3        | 1          | 
| 2014 | July  | 7         | Mental Hygiene | Living Alone                   | 4          | 
| 2014 | July  | 7         | Mental Hygiene | Living in Household of Another | 2          | 
| 2014 | July  | 7         | Mental Hygiene | Living With Others             | 20         | 
| 2014 | July  | 7         | Mental Hygiene | Other                          | 1557       | 
| 2014 | July  | 7         | Mental Hygiene | Title XIX Institution          | 773        | 
| 2014 | July  | 7         | New York City  | Congregate Care Level 1        | 299        | 
| 2014 | July  | 7         | New York City  | Congregate Care Level 2        | 9612       | 
```