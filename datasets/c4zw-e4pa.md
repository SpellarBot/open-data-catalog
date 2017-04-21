# Excess Revenues for Battery Park City Authority (BPCA) Provided to NYC Annually: Beginning 1987

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/excess-revenues-for-battery-park-city-authority-bpca-provided-to-nyc-annually-beginning-19) |
| Metadata | [Link](https://data.ny.gov/api/views/c4zw-e4pa) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/c4zw-e4pa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/c4zw-e4pa/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | c4zw-e4pa |
| Name | Excess Revenues for Battery Park City Authority (BPCA) Provided to NYC Annually: Beginning 1987 |
| Attribution | Battery Park City Authority |
| Category | Government & Finance |
| Tags | bpca, excess revenues |
| Created | 2013-11-15T19:27:37Z |
| Publication Date | 2016-10-21T15:44:41Z |

## Description

The disposition and allocation of annual Excess Revenues is governed by the 1986 amendment to the Settlement Agreement which defined the relationship between the Authority and the City of New York.

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | time           | year       | Year   | number    | number      |
| Yes      | numeric metric | amount     | Amount | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:c4zw-e4pa d:1987-01-01T00:00:00.000Z m:amount=5700000

series e:c4zw-e4pa d:1988-01-01T00:00:00.000Z m:amount=22494385

series e:c4zw-e4pa d:1989-01-01T00:00:00.000Z m:amount=31889000
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

entity e:c4zw-e4pa l:"Excess Revenues for Battery Park City Authority (BPCA) Provided to NYC Annually: Beginning 1987" t:attribution="Battery Park City Authority" t:url=https://data.ny.gov/api/views/c4zw-e4pa

property e:c4zw-e4pa t:meta.view v:id=c4zw-e4pa v:category="Government & Finance" v:attributionLink=http://www.bpca.ny.gov/ v:averageRating=0 v:name="Excess Revenues for Battery Park City Authority (BPCA) Provided to NYC Annually: Beginning 1987" v:attribution="Battery Park City Authority"

property e:c4zw-e4pa t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:c4zw-e4pa t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:c4zw-e4pa t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | amount   | 
| ==== | ======== | 
| 1987 | 5700000  | 
| 1988 | 22494385 | 
| 1989 | 31889000 | 
| 1990 | 27186637 | 
| 1991 | 42332067 | 
| 1992 | 30030158 | 
| 1993 | 18078000 | 
| 1994 | 24548750 | 
| 1995 | 34118000 | 
| 1996 | 34804443 | 
```