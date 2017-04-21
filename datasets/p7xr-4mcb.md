# Missouri First Reports of Injury by County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-first-reports-of-injury-by-county-99cdb) |
| Metadata | [Link](https://data.mo.gov/api/views/p7xr-4mcb) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/p7xr-4mcb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/p7xr-4mcb/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | p7xr-4mcb |
| Name | Missouri First Reports of Injury by County |
| Category | Labor |
| Tags | employment, injury, froi, labor |
| Created | 2012-09-25T14:27:41Z |
| Publication Date | 2013-01-03T20:46:25Z |

## Description

First reports of injury by county based on accident site location zip code.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name     | Data Type | Render Type |
| ======== | ============== | ============= | ======== | ========= | =========== |
| Yes      | series tag     | recordid      | recordid | text      | text        |
| Yes      | time           | year          | year     | number    | number      |
| Yes      | numeric metric | monthasnumber | month    | number    | number      |
| Yes      | series tag     | county        | county   | text      | text        |
| Yes      | numeric metric | count         | count    | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:p7xr-4mcb d:2010-01-01T00:00:00.000Z t:county=MISSING t:recordid=2-2010-MISSING m:monthasnumber=2 m:count=2

series e:p7xr-4mcb d:2004-01-01T00:00:00.000Z t:county=MISSING t:recordid=12-2004-MISSING m:monthasnumber=12 m:count=1

series e:p7xr-4mcb d:2008-01-01T00:00:00.000Z t:county=MISSING t:recordid=8-2008-MISSING m:monthasnumber=8 m:count=6
```

## Meta Commands

```ls
metric m:monthasnumber p:integer l:month t:dataTypeName=number

metric m:count p:integer l:count t:dataTypeName=number

entity e:p7xr-4mcb l:"Missouri First Reports of Injury by County" t:url=https://data.mo.gov/api/views/p7xr-4mcb

property e:p7xr-4mcb t:meta.view v:id=p7xr-4mcb v:category=Labor v:averageRating=0 v:name="Missouri First Reports of Injury by County"

property e:p7xr-4mcb t:meta.view.owner v:id=fq9d-b9a3 v:screenName=Jolene v:displayName=Jolene

property e:p7xr-4mcb t:meta.view.tableauthor v:id=fq9d-b9a3 v:screenName=Jolene v:roleName=editor v:displayName=Jolene
```

## Top Records

```ls
| recordid        | year | monthasnumber | county  | count | 
| =============== | ==== | ============= | ======= | ===== | 
| 2-2010-MISSING  | 2010 | 2             | MISSING | 2     | 
| 12-2004-MISSING | 2004 | 12            | MISSING | 1     | 
| 8-2008-MISSING  | 2008 | 8             | MISSING | 6     | 
| 4-2005-MISSING  | 2005 | 4             | MISSING | 1     | 
| 10-2006-MISSING | 2006 | 10            | MISSING | 1     | 
| 5-2005-MISSING  | 2005 | 5             | MISSING | 1     | 
| 12-2009-MISSING | 2009 | 12            | MISSING | 1     | 
| 11-2005-MISSING | 2005 | 11            | MISSING | 1     | 
| 4-2010-MISSING  | 2010 | 4             | MISSING | 1     | 
| 3-2007-MISSING  | 2007 | 3             | MISSING | 2     | 
```