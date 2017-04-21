# Enterprise Zone Enrollment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/enterprise-zone-enrollment-70118) |
| Metadata | [Link](https://data.hawaii.gov/api/views/nhut-yk4g) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/nhut-yk4g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/nhut-yk4g/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | nhut-yk4g |
| Name | Enterprise Zone Enrollment |
| Category | Economic Development |
| Created | 2013-06-06T00:31:23Z |
| Publication Date | 2013-06-06T00:33:07Z |

## Description

Enterprise Zone Enrollment

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | time           | year       | Year     | number    | text        |
| Yes      | numeric metric | existing   | Existing | number    | number      |
| Yes      | numeric metric | new        | New      | number    | number      |
| Yes      | numeric metric | total      | Total    | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nhut-yk4g d:2001-01-01T00:00:00.000Z m:total=5 m:new=5 m:existing=0

series e:nhut-yk4g d:2002-01-01T00:00:00.000Z m:total=20 m:new=15 m:existing=5

series e:nhut-yk4g d:2003-01-01T00:00:00.000Z m:total=38 m:new=18 m:existing=20
```

## Meta Commands

```ls
metric m:existing p:integer l:Existing t:dataTypeName=number

metric m:new p:integer l:New t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:nhut-yk4g l:"Enterprise Zone Enrollment" t:url=https://data.hawaii.gov/api/views/nhut-yk4g

property e:nhut-yk4g t:meta.view v:id=nhut-yk4g v:category="Economic Development" v:averageRating=0 v:name="Enterprise Zone Enrollment"

property e:nhut-yk4g t:meta.view.owner v:id=686a-saa8 v:screenName=Cy v:displayName=Cy

property e:nhut-yk4g t:meta.view.tableauthor v:id=686a-saa8 v:screenName=Cy v:roleName=publisher v:displayName=Cy
```

## Top Records

```ls
| year | existing | new | total | 
| ==== | ======== | === | ===== | 
| 2001 | 0        | 5   | 5     | 
| 2002 | 5        | 15  | 20    | 
| 2003 | 20       | 18  | 38    | 
| 2004 | 38       | 2   | 40    | 
| 2005 | 40       | 26  | 66    | 
| 2006 | 66       | 22  | 88    | 
| 2007 | 88       | 29  | 117   | 
| 2008 | 112      | 14  | 126   | 
| 2009 | 108      | 41  | 149   | 
| 2010 | 147      | 58  | 205   | 
```